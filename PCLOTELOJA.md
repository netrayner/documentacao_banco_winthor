# 📊 Tabela: PCLOTELOJA

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOTELOJA    CODFILIAL  VARCHAR2(2)                                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTELOJA      CODPROD  NUMBER(6,0)                               Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTELOJA      NUMLOTE VARCHAR2(15)                                  Número do lote    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTELOJA           QT NUMBER(22,6)                                      Quantidade            OPERACIONAL                        NaN
PCLOTELOJA   DTULMOVSAI         DATE            Data da última movimentação de saída            OPERACIONAL                        NaN
PCLOTELOJA   DTULMOVENT         DATE          Data da última movimentação de entrada            OPERACIONAL                        NaN
PCLOTELOJA   DTVALIDADE         DATE                                Data de validade            OPERACIONAL                        NaN
PCLOTELOJA  QTBLOQUEADA NUMBER(22,6)                            Quantidade bloqueada            OPERACIONAL                        NaN
PCLOTELOJA  NUMTRANSENT NUMBER(10,0)                  Número da transação de entrada            OPERACIONAL                        NaN
PCLOTELOJA CODAGREGACAO VARCHAR2(20) Responsavel por armazenar o código de agregação            OPERACIONAL                        NaN
PCLOTELOJA DTFABRICACAO         DATE                      Data de fabricação do lote            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*