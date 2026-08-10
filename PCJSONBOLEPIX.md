# 📊 Tabela: PCJSONBOLEPIX

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCJSONBOLEPIX            DATA TIMESTAMP(6)             Data geração log            OPERACIONAL                        NaN
PCJSONBOLEPIX            TIPO VARCHAR2(12)          Tipo geração do log            OPERACIONAL                        NaN
PCJSONBOLEPIX   NUMTRANSVENDA NUMBER(10,0) Numero de transação de venda            OPERACIONAL                        NaN
PCJSONBOLEPIX           PREST  VARCHAR2(2)                   Prestação             OPERACIONAL                        NaN
PCJSONBOLEPIX NOSSONUMBOLEPIX NUMBER(14,0)                Nº de bolepix            OPERACIONAL                        NaN
PCJSONBOLEPIX            JSON         CLOB           Json gerado na API            OPERACIONAL                        NaN
PCJSONBOLEPIX     INFORETORNO         CLOB                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*