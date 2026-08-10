# 📊 Tabela: PCLOGTRANSFCARTEIRA

### Estrutura de Colunas e Restrições

             Tabela           Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGTRANSFCARTEIRA CODTRANSFERENCIA   NUMBER(6,0)                      Código da transação de transferência    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGTRANSFCARTEIRA  CODUSURANTERIOR   NUMBER(4,0)                                      Código do RCA antigo    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGTRANSFCARTEIRA     CODUSURATUAL   NUMBER(4,0)                                       Código do RCA atual            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA           CODCLI   NUMBER(6,0)                           Código do cliente a transferido            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA           MOTIVO VARCHAR2(200)                                   Motivo da transferência            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA       DTINCLUSAO          DATE            Data de inclusão no log, data de transferência            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA    CODUSUARIOINC   NUMBER(8,0)            Código do usuário que realizou a transferência            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA        DTESTORNO          DATE                          Data de estorno da transferência            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA    CODUSUARIOEST   NUMBER(8,0) Código do usuário que realizou o estorno da transferência            OPERACIONAL                        NaN
PCLOGTRANSFCARTEIRA     ORIGEMTRANSF   VARCHAR2(1)                          Guarda a origem da transferencia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*