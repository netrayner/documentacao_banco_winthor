# 📊 Tabela: PCSUGESTAOCOMPRAC

### Estrutura de Colunas e Restrições

           Tabela              Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGESTAOCOMPRAC         NUMSUGESTAO NUMBER(10,0)                                           Núm. Sugestão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOCOMPRAC           CODFORNEC  NUMBER(6,0)                                         Cód. Fornecedor.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC           CODFILIAL  VARCHAR2(2)                                             Cód. Filial.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC  CODUSUARIOSUGESTAO  NUMBER(8,0)                                   Cód. Usuário Sugestão.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC        DATASUGESTAO         DATE                                           Data Sugestão.            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC           CODEDITAL  NUMBER(9,0)                                         Código do edital            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC        TIPODESCARGA  VARCHAR2(1) Tipo do pedido de compra ( 1 - Normal / 5 - Bonificado )            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC          IMPORTACAO  VARCHAR2(1)      Identificar que o pedido de compra já foi importado            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC TIPOEMBALAGEMPEDIDO  VARCHAR2(1)                                 Tipo embalagem do pedido            OPERACIONAL                        NaN
PCSUGESTAOCOMPRAC           DTPREVENT         DATE                              Data de previsão de entrega            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*