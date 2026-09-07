# 📊 Tabela: PCLIMITECOMPRAPERIODO

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLIMITECOMPRAPERIODO    DATAINICIAL         DATE                    Data inicial do período do limite de compra por comprador.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO      DATAFINAL         DATE                      Data final do período do limite de compra por comprador.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO   CODCOMPRADOR  NUMBER(8,0) Código do comprador para lançamento do valor de limite de compra por período.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO    VALORLIMITE NUMBER(18,6)                              Valor limite do período de compra por comprador.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO      CODFILIAL  VARCHAR2(2)                                        GRAVAR O CODIGO DA FILIAL NO REGISTRO.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO      CODFORNEC  NUMBER(6,0)                                    GRAVAR O CODIGO DO FORNECEDOR NO REGISTRO.            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO       CODGRUPO NUMBER(10,0)                                                    Código do grupo de filiais            OPERACIONAL                        NaN
PCLIMITECOMPRAPERIODO LIMITEPORGRUPO  VARCHAR2(1)                                                    Limite por gurpo de filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*