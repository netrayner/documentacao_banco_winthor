# 📊 Tabela: PCREMESSAPRODUCAO

### Estrutura de Colunas e Restrições

           Tabela     Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREMESSAPRODUCAO       DATA           DATE                   Data atual da inserção            OPERACIONAL                        NaN
PCREMESSAPRODUCAO  CODFILIAL   VARCHAR2(20)             Filial da emissão da remessa            OPERACIONAL                        NaN
PCREMESSAPRODUCAO QUANTIDADE   NUMBER(20,6) Quantidade de itens inseridos na remessa            OPERACIONAL                        NaN
PCREMESSAPRODUCAO     STATUS    VARCHAR2(1)                        STATUS DA REMESSA            OPERACIONAL                        NaN
PCREMESSAPRODUCAO   DTCANCEL           DATE                     Data de cancelamento            OPERACIONAL                        NaN
PCREMESSAPRODUCAO  DESCRICAO  VARCHAR2(250)                          Descrição Curta            OPERACIONAL                        NaN
PCREMESSAPRODUCAO NUMREMESSA   NUMBER(20,0)                 Identificador da remessa    CHAVE PRIMÁRIA (PK)                        NaN
PCREMESSAPRODUCAO        OBS VARCHAR2(1000)                               Observação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*