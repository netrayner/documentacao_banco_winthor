# 📊 Tabela: PCCOTACAOMOEDAI

### Estrutura de Colunas e Restrições

         Tabela         Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOMOEDAI         CODIGO  NUMBER(6,0)                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOMOEDAI    DATACOTACAO         DATE                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOMOEDAI        COTACAO NUMBER(18,6)                                       NaN            OPERACIONAL                        NaN
PCCOTACAOMOEDAI  COTACAOCOMPRA NUMBER(12,6) Valor da Cotação Livre (Compra) da moeda.            OPERACIONAL                        NaN
PCCOTACAOMOEDAI   COTACAOVENDA NUMBER(12,6)  Valor da Cotação Livre (Venda) da moeda.            OPERACIONAL                        NaN
PCCOTACAOMOEDAI   TIPOPARIDADE  VARCHAR2(1)                          Tipo de paridade            OPERACIONAL                        NaN
PCCOTACAOMOEDAI PARIDADECOMPRA NUMBER(12,6)    Paridade em relação ao dolar de compra            OPERACIONAL                        NaN
PCCOTACAOMOEDAI  PARIDADEVENDA NUMBER(12,6)     Paridade em relação ao dolar de venda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*