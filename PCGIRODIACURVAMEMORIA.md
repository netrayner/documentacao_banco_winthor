# 📊 Tabela: PCGIRODIACURVAMEMORIA

### Estrutura de Colunas e Restrições

               Tabela          Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIACURVAMEMORIA         CODPROD NUMBER(10,0)                    Identificador único do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAMEMORIA       CODFILIAL  VARCHAR2(2)                                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAMEMORIA     TIPOANALISE  VARCHAR2(1)                   Tipo de analise da curva F ou Q    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIACURVAMEMORIA QUANTIDADETOTAL NUMBER(16,2)               Quantidade total de venda analisada            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA      VENDATOTAL NUMBER(16,2)                    Valor total de venda analisada            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA      PRECOMEDIO NUMBER(16,2)                   Preço médio no periodo da curva            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA         GIRODIA NUMBER(16,2)          Valor de giro diário no periodo da curva            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA     PORCENTAGEM NUMBER(16,2)         Porcentagem do produto referente ao lucro            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA    PARTICIPACAO NUMBER(16,2)     Participação do produto referente a Curva ABC            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA      CHAVECURVA VARCHAR2(30)     Identificador da curva que o produto pertence            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA       TIPOCURVA  VARCHAR2(1)     Tipo de curva (F ou Q) que o produto pertence            OPERACIONAL                        NaN
PCGIRODIACURVAMEMORIA   CHAVESUBCURVA VARCHAR2(30) Identificador da sub-curva que o produto pertence            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*