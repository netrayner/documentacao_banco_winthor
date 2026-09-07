# 📊 Tabela: PCVARIAVELLAYOUT

### Estrutura de Colunas e Restrições

          Tabela            Coluna Tipo/Tamanho                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVELLAYOUT            CODIGO NUMBER(10,0)                                                                  Código identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVELLAYOUT       CODVARIAVEL NUMBER(10,0)                                                                      Nome da variável CHAVE ESTRANGEIRA (FK)           PCVARIAVELBOLETO
PCVARIAVELLAYOUT         CODLAYOUT NUMBER(10,0)                                                       Código na tabela PCLAYOUTBOLETO CHAVE ESTRANGEIRA (FK)             PCLAYOUTBOLETO
PCVARIAVELLAYOUT    POSICAOINICIAL  NUMBER(4,0)                                                 Posição inicial da variável no layout            OPERACIONAL                        NaN
PCVARIAVELLAYOUT      POSICAOFINAL  NUMBER(4,0)                                                   Posição final da variável no layout            OPERACIONAL                        NaN
PCVARIAVELLAYOUT DIGITOVERIFICADOR      CHAR(1)                             Informa se variável é digito verificador no layout ou não            OPERACIONAL                        NaN
PCVARIAVELLAYOUT              TIPO  VARCHAR2(2) Tipo da variável no layout: P(POSICAO), BC(Banco Correspondente), LD(Linha digitavel)            OPERACIONAL                        NaN
PCVARIAVELLAYOUT             VALOR VARCHAR2(50)                                                                Valor fixo da variável            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*