# 📊 Tabela: PCVASILHAMEEMB

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVASILHAMEEMB    CODVASILHAME  NUMBER(6,0)       Codigo Vasilhame            OPERACIONAL                        NaN
PCVASILHAMEEMB       DESCRICAO VARCHAR2(40) Descricao do vasilhame            OPERACIONAL                        NaN
PCVASILHAMEEMB    PERMITEVENDA  VARCHAR2(1)          Permite venda            OPERACIONAL                        NaN
PCVASILHAMEEMB          PVENDA NUMBER(12,3)         Preço de venda            OPERACIONAL                        NaN
PCVASILHAMEEMB     CODAUXILIAR NUMBER(20,0)        Codigo Auxiliar    CHAVE PRIMÁRIA (PK)                        NaN
PCVASILHAMEEMB       CODFILIAL  VARCHAR2(2)          Codigo Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCVASILHAMEEMB      DTEXCLUSAO         DATE                    NaN            OPERACIONAL                        NaN
PCVASILHAMEEMB USUARIOEXCLUSAO  VARCHAR2(4)                    NaN            OPERACIONAL                        NaN
PCVASILHAMEEMB       ENGRADADO  VARCHAR2(1)            VARCHAR2(1)            OPERACIONAL                        NaN
PCVASILHAMEEMB CONTROLAESTOQUE  VARCHAR2(1)            VARCHAR2(1)            OPERACIONAL                        NaN
PCVASILHAMEEMB         CODPROD  NUMBER(6,0)              NUMBER(6)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*