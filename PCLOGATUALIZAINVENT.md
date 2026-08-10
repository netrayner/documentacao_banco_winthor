# 📊 Tabela: PCLOGATUALIZAINVENT

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGATUALIZAINVENT      CODFILIAL  VARCHAR2(2)                       Código da filial do inventário            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT           DATA         DATE                    Data de atualização do inventário            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT      NUMINVENT  NUMBER(8,0)                      Número do inventário atualizado            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT        CODPROD  NUMBER(6,0)                      Código do produto do inventário            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT        NUMLOTE VARCHAR2(15)                            Número do lote do produto            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT       QTINVENT NUMBER(22,8)                                Quantidade atualizada            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT       QTESTGER NUMBER(22,8)                                        Estoque atual            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT        PERCDIF NUMBER(22,8) Percentual de diferença entre o estoque e a contagem            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT CUSTOUTILIZADO VARCHAR2(50)                      O custo utilizado no inventário            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT        VLCUSTO NUMBER(22,8)                             Valor do custo utilizado            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT          QTDIF NUMBER(22,8)                              Quantidade de diferença            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT          VLDIF NUMBER(22,8)                                   Valor da diferança            OPERACIONAL                        NaN
PCLOGATUALIZAINVENT     TIPOAJUSTE  VARCHAR2(2)                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*