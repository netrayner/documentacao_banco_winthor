# 📊 Tabela: PCREMESSAPRODUCAOI

### Estrutura de Colunas e Restrições

            Tabela      Coluna  Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREMESSAPRODUCAOI  NUMREMESSA  NUMBER(20,0)                   Identificador do ítem da remessa    CHAVE PRIMÁRIA (PK)                        NaN
PCREMESSAPRODUCAOI     CODPROD  NUMBER(20,0)                                  codido do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCREMESSAPRODUCAOI  QUANTIDADE  NUMBER(20,6)           Quantidade de itens inseridos na remessa            OPERACIONAL                        NaN
PCREMESSAPRODUCAOI     NUMLOTE  VARCHAR2(20)                     NUMLOTE do produto , se houver    CHAVE PRIMÁRIA (PK)                        NaN
PCREMESSAPRODUCAOI QTINDUSTRIA  NUMBER(20,6) Quantidade indústria de itens inseridos na remessa            OPERACIONAL                        NaN
PCREMESSAPRODUCAOI   DESCRICAO VARCHAR2(250)                                    Descrição Curta            OPERACIONAL                        NaN
PCREMESSAPRODUCAOI QTBLOQUEADA  NUMBER(20,6)                               Quantidade bloqueada            OPERACIONAL                        NaN
PCREMESSAPRODUCAOI      NUMSEQ  NUMBER(20,0)                              Sequência de inserção    CHAVE PRIMÁRIA (PK)                        NaN
PCREMESSAPRODUCAOI       NUMOP   NUMBER(8,0)                                Num. Ordem Producao            OPERACIONAL                        NaN
PCREMESSAPRODUCAOI    NUMSEQAP  NUMBER(20,0)                    Num. Do Apontamento de Produção            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*