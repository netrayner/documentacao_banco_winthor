# 📊 Tabela: PCEMBALAGEMVARIANTEFILIAL

### Estrutura de Colunas e Restrições

                   Tabela                Coluna Tipo/Tamanho       Descrição da Coluna Restrição (Constraint)   Tabela Relacionada (Se FK)
PCEMBALAGEMVARIANTEFILIAL                    ID NUMBER(10,0)    Registro identificador    CHAVE PRIMÁRIA (PK)                          NaN
PCEMBALAGEMVARIANTEFILIAL            VARIANTEID NUMBER(10,0) Identificador da variante CHAVE ESTRANGEIRA (FK) PCEMBALAGEMECOMMERCEVARIANTE
PCEMBALAGEMVARIANTEFILIAL             CODFILIAL  VARCHAR2(2)          Código da filial CHAVE ESTRANGEIRA (FK)                     PCFILIAL
PCEMBALAGEMVARIANTEFILIAL       CODIGOECOMMERCE NUMBER(10,0)       Código do ecommerce            OPERACIONAL                          NaN
PCEMBALAGEMVARIANTEFILIAL DATAULTIMAATUALIZACAO         DATE Data a última atualização            OPERACIONAL                          NaN

---
*Documentação gerada automaticamente.*