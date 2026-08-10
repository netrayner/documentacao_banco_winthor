# 📊 Tabela: PCFUNDOMULTIFILIAL

### Estrutura de Colunas e Restrições

            Tabela       Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFUNDOMULTIFILIAL     CODFUNDO  NUMBER(6,0) codigo gerado pela nova rotina de cadastro para identificar o fundo.            OPERACIONAL                        NaN
PCFUNDOMULTIFILIAL    CODFORNEC  NUMBER(6,0)              Código do fornecedor para identificar o saldo do fundo.            OPERACIONAL                        NaN
PCFUNDOMULTIFILIAL CODCOMPRADOR  NUMBER(8,0)               Código do comprador para identificar o saldo do fundo.            OPERACIONAL                        NaN
PCFUNDOMULTIFILIAL        VALOR NUMBER(18,6)                                              Valor do saldo do fundo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*