# 📊 Tabela: PCULTIMODIGITOVENDA

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho                                                                                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCULTIMODIGITOVENDA    DIGITOATUAL  NUMBER(1,0)                                                                                                           Este dígito será substituido pelo dígito novo nos preços das embalagens.            OPERACIONAL                        NaN
PCULTIMODIGITOVENDA     DIGITONOVO  NUMBER(1,0)                                                                                                              Este dígito substituirá o dígito original nos preços das sembalagens.            OPERACIONAL                        NaN
PCULTIMODIGITOVENDA TIPOPROXDIGITO  VARCHAR2(2) Este parâmetro é utilizado para informar se para chegar no novo dígito será incrementado ou decrementado o valor original, ou seja, o valor será alterado para mais ou para menos.            OPERACIONAL                        NaN
PCULTIMODIGITOVENDA       CODFAIXA  NUMBER(6,0)                                                                                                                                                  Codigo da faixa de arredondamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*