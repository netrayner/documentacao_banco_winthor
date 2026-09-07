# 📊 Tabela: PCLOGHISTEST

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGHISTEST      CODFILIAL  VARCHAR2(2)                                            Campos para identificação da filial no Log||Campo do tipo caracter, de tamanho 2            OPERACIONAL                        NaN
PCLOGHISTEST        CODPROD  NUMBER(6,0)                       Campos para identificação do produto no Log||Campo do tipo numérico, de tamanho 8, sem casas decimais            OPERACIONAL                        NaN
PCLOGHISTEST       QTESTANT NUMBER(22,8)    Campos para identificação da quantidade de estoque anterior||Campo do tipo numérico, de tamanho 22, com 8 casas decimais            OPERACIONAL                        NaN
PCLOGHISTEST     QTESTATUAL NUMBER(22,8)       Campos para identificação da quantidade de estoque atual||Campo do tipo numérico, de tamanho 22, com 8 casas decimais            OPERACIONAL                        NaN
PCLOGHISTEST   CUSTOCONTANT NUMBER(18,8)           Campos para identificação do custo contábil anterior||Campo do tipo numérico, de tamanho 18, com 6 casas decimais            OPERACIONAL                        NaN
PCLOGHISTEST CUSTOCONTATUAL NUMBER(18,8)              Campos para identificação do custo contábil atual||Campo do tipo numérico, de tamanho 18, com 6 casas decimais            OPERACIONAL                        NaN
PCLOGHISTEST        DTALTER         DATE                                         Campos para identificação da data em que foi alterado o estoque||Campo do tipo data            OPERACIONAL                        NaN
PCLOGHISTEST     ALTERPCEST  VARCHAR2(2) Campos para identificar se o usuário permitiu que alterasse também o Estoque (PCEST).||Campo do tipo caracter, de tamanho 2            OPERACIONAL                        NaN
PCLOGHISTEST   CODFUNCALTER  NUMBER(8,0)                                                                 Campos para identificação do usuário que alterou o estoque.            OPERACIONAL                        NaN
PCLOGHISTEST           DATA         DATE                                                                                         Indica a data historica do estoque.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*