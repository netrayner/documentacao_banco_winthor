# 📊 Tabela: PCPEDICMVRESULTADO

### Estrutura de Colunas e Restrições

            Tabela     Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDICMVRESULTADO     NUMPED  NUMBER(10,0)                                         Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMVRESULTADO    CODPROD   NUMBER(6,0)                                        Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMVRESULTADO     NUMSEQ  NUMBER(20,0)             Número de sequência do item dentro do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMVRESULTADO CODFORMULA VARCHAR2(200)                              Código da fórmula utilizado    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMVRESULTADO   REGISTRO VARCHAR2(100) Código do atributo retornado, podendo ser um sub-formula    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDICMVRESULTADO      VALOR  NUMBER(22,6)                                          Valor retornado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*