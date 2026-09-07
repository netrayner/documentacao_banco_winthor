# 📊 Tabela: PCHISTMOVINSERVIVEL

### Estrutura de Colunas e Restrições

             Tabela               Coluna   Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTMOVINSERVIVEL CODHISTMOVINSERVIVEL    NUMBER(6,0) Código identificador sequencial para historico de movimentação de inservível    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTMOVINSERVIVEL     CODMOVINSERVIVEL    NUMBER(6,0)                    Código da movimentação que este registro de log se refere            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL           DTREGISTRO           DATE                                                Data de registro do histórico            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL               ROTINA   VARCHAR2(50)                                  Nome da rotina que foi executado a operação            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL              USUARIO   VARCHAR2(30)                                      Nome do usuário que realizou a operação            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL          EQUIPAMENTO   VARCHAR2(70)                         Nome do equipamento de onde foi realizado a operação            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL              SALDOKG   NUMBER(12,6)                                                Novo saldo de Carcaça em (KG)            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL           SALDOKGANT   NUMBER(12,6)                                            Saldo anterior de Carcaça em (KG)            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL              SALDOVL   NUMBER(18,6)                                            Novo saldo de Carcaça em Valor R$            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL           SALDOVLANT   NUMBER(18,6)                                        Saldo anterior de Carcaça em Valor R$            OPERACIONAL                        NaN
PCHISTMOVINSERVIVEL            HISTORICO VARCHAR2(1000)                                               Historico do que foi realizado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*