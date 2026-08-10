# 📊 Tabela: PCVARIAVELLAYOUTBANCARIO

### Estrutura de Colunas e Restrições

                  Tabela          Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVELLAYOUTBANCARIO          CODIGO NUMBER(10,0) Codigo de sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVELLAYOUTBANCARIO     CODVARIAVEL NUMBER(10,0)  Codigo da variavel CHAVE ESTRANGEIRA (FK)         PCVARIAVELBANCARIA
PCVARIAVELLAYOUTBANCARIO       CODLAYOUT NUMBER(10,0)    Codigo do layout CHAVE ESTRANGEIRA (FK)           PCLAYOUTBANCARIO
PCVARIAVELLAYOUTBANCARIO  POSICAOINICIAL  NUMBER(4,0)     Posicao inicial            OPERACIONAL                        NaN
PCVARIAVELLAYOUTBANCARIO    POSICAOFINAL  NUMBER(4,0)       Posicao final            OPERACIONAL                        NaN
PCVARIAVELLAYOUTBANCARIO           VALOR VARCHAR2(50)   Valor Da variavel            OPERACIONAL                        NaN
PCVARIAVELLAYOUTBANCARIO CODIGO_REGISTRO NUMBER(10,0)  Codigo do registro CHAVE ESTRANGEIRA (FK)  PCESTRUTURALAYOUTREGISTRO

---
*Documentação gerada automaticamente.*