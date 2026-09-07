# 📊 Tabela: PCATIVI

### Estrutura de Colunas e Restrições

 Tabela            Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCATIVI           CODATIV  NUMBER(6,0)                                                    Código atividade.    CHAVE PRIMÁRIA (PK)                        NaN
PCATIVI              RAMO VARCHAR2(40)                                                                Ramo.            OPERACIONAL                        NaN
PCATIVI          PERCDESC  NUMBER(5,2)                                              Percentual de desconto.            OPERACIONAL                        NaN
PCATIVI             CODCP  VARCHAR2(6)                                                           Código CP.            OPERACIONAL                        NaN
PCATIVI CODCATEGORIAKRAFT  NUMBER(2,0)                                              Código categoria KRAFT.            OPERACIONAL                        NaN
PCATIVI     CODRAMONESTLE  NUMBER(6,0)                                                  Código ramo Nestle.            OPERACIONAL                        NaN
PCATIVI CODCATEGORIABAUDU VARCHAR2(10)                                              Código Categoria BAUDU.            OPERACIONAL                        NaN
PCATIVI        ATACADISTA  VARCHAR2(1) Campo para identificação se o ramo de atividade é atacadista ou não.            OPERACIONAL                        NaN
PCATIVI               COR VARCHAR2(30)                                                                 Cor.            OPERACIONAL                        NaN
PCATIVI      CODATIVPRINC  NUMBER(6,0)                     Indica o código do ramo de atividade principal..            OPERACIONAL                        NaN
PCATIVI    PERCREDALIQIPI NUMBER(18,6)                             Percentual de Redução da Alíquota de IPI            OPERACIONAL                        NaN
PCATIVI         CALCULAST  VARCHAR2(1)            Define se irá calcular ST ou não para o ramo de atividade            OPERACIONAL                        NaN
PCATIVI     CATVAREJODORI  VARCHAR2(5)                         Categoria do varejo para integração com DORI            OPERACIONAL                        NaN
PCATIVI        DTMXSALTER         DATE                                                                  NaN            OPERACIONAL                        NaN
PCATIVI     DATAALTERACAO         DATE                      Indica a última vez que a tabela foi modificada            OPERACIONAL                        NaN
PCATIVI      DATACADASTRO         DATE                                            Indica a data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*