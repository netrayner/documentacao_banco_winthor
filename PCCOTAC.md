# 📊 Tabela: PCCOTAC

### Estrutura de Colunas e Restrições

 Tabela        Coluna Tipo/Tamanho                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTAC   NUMPESQUISA NUMBER(10,0)                                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAC       CODPROD  NUMBER(6,0)                                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAC   DATAGERACAO         DATE                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC     CODFILIAL  VARCHAR2(2)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC      CODPLPAG  NUMBER(4,0)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC     NUMREGIAO  NUMBER(4,0)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC     DESCRICAO VARCHAR2(40)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC     EMBALAGEM VARCHAR2(12)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC   CODFUNCGERA  NUMBER(8,0)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC DESCRICAOPESQ VARCHAR2(40)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC          TIPO  VARCHAR2(2)                                                                                                  NaN            OPERACIONAL                        NaN
PCCOTAC   CODAUXILIAR NUMBER(16,0)                                                            Código auxiliar da embalagem a ser cotada    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAC      SITUACAO  VARCHAR2(2) Este campo é para dizer qual a situação da cotação que está sendo feita, se é Em edição e concluída.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*