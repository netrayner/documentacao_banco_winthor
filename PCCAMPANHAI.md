# 📊 Tabela: PCCAMPANHAI

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAMPANHAI CODCAMPANHA NUMBER(10,0)                                                           Indica o código da campanha de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPANHAI     CODPROD  NUMBER(6,0)                                    Indica o código do produto pertencente à campanha de vendas.    CHAVE PRIMÁRIA (PK)                        NaN
PCCAMPANHAI   CODFORNEC  NUMBER(6,0)                                                       Indica o código do fornecedor do produto.            OPERACIONAL                        NaN
PCCAMPANHAI OBRIGATORIO  VARCHAR2(1) Indica se este produto será ou não obrigatório a venda para considerar como cliente positivado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*