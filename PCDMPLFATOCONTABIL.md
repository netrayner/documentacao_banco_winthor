# 📊 Tabela: PCDMPLFATOCONTABIL

### Estrutura de Colunas e Restrições

            Tabela          Coluna  Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDMPLFATOCONTABIL         CODDMPL  NUMBER(10,0)                                                        Código DMPL    CHAVE PRIMÁRIA (PK)                     PCDMPL
PCDMPLFATOCONTABIL CODFATOCONTABIL  VARCHAR2(20)                                               Código Fato Contábil    CHAVE PRIMÁRIA (PK)                        NaN
PCDMPLFATOCONTABIL       DESCRICAO VARCHAR2(100)                                                          Descrição            OPERACIONAL                        NaN
PCDMPLFATOCONTABIL           ATIVO   VARCHAR2(1)                                                              Ativo            OPERACIONAL                        NaN
PCDMPLFATOCONTABIL     TOTALIZADOR   VARCHAR2(1)                         Define se a fato contábil é de totalização            OPERACIONAL                        NaN
PCDMPLFATOCONTABIL           ORDEM   NUMBER(5,0) Ordem dos fatos contábeis a serem seguidos na estrutura automática            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*