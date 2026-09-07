# 📊 Tabela: PCPESQUISA

### Estrutura de Colunas e Restrições

    Tabela       Coluna   Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPESQUISA  CODPESQUISA    NUMBER(8,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPESQUISA NOMEPESQUISA   VARCHAR2(60)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA    MATRICULA    NUMBER(8,0)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA         DATA           DATE                                  NaN            OPERACIONAL                        NaN
PCPESQUISA TIPORESPOSTA    VARCHAR2(1)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA     NUMMANIF    NUMBER(8,0)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA       NUMSEQ    NUMBER(2,0)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA       SCRIPT VARCHAR2(4000)                                  NaN            OPERACIONAL                        NaN
PCPESQUISA     DTINICIO           DATE Indica a data de inicio da pesquisa.            OPERACIONAL                        NaN
PCPESQUISA        DTFIM           DATE  Indica a data de final da pesquisa.            OPERACIONAL                        NaN
PCPESQUISA        ATIVA    VARCHAR2(1)     Indica se a pesquisa esta ativa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*