# 📊 Tabela: PCESTCR

### Estrutura de Colunas e Restrições

 Tabela                Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTCR              CODBANCO  NUMBER(4,0)                                               Código de banco ou caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCR                CODCOB  VARCHAR2(4) Código da moeda (nessa tabela é representada por moeda e não cobrança).    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCR                 VALOR NUMBER(16,2)                            Valor do saldo final padrao por conciliação.            OPERACIONAL                        NaN
PCESTCR       VALORCONCILIADO NUMBER(16,2)                                                        Valor Conciliado            OPERACIONAL                        NaN
PCESTCR         DTULTCONCILIA         DATE                                             Data da ultima conciliação.            OPERACIONAL                        NaN
PCESTCR VALORSALDOTOTALCONCIL NUMBER(16,2)                              Valor do novo saldo final por conciliação.            OPERACIONAL                        NaN
PCESTCR   VALORSALDOTOTALCOMP NUMBER(16,2)                              Valor do novo saldo final por compensação.            OPERACIONAL                        NaN
PCESTCR       VALORCOMPENSADO NUMBER(16,2)                                  Valor de saldo somente de compensados.            OPERACIONAL                        NaN
PCESTCR      DTULTCOMPENSACAO         DATE                                             Data da ultima compensação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*