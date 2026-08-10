# 📊 Tabela: PCLOGPEDIDOAPI

### Estrutura de Colunas e Restrições

        Tabela   Coluna Tipo/Tamanho                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPEDIDOAPI     DATA         DATE                                                                                Data de registro            OPERACIONAL                        NaN
PCLOGPEDIDOAPI   NUMPED NUMBER(10,0)                                                                                Número do pedido            OPERACIONAL                        NaN
PCLOGPEDIDOAPI  POSICAO  VARCHAR2(1)                                                                               Posição do pedido            OPERACIONAL                        NaN
PCLOGPEDIDOAPI OPERACAO  VARCHAR2(1) Define qual o tipo de opeção está sendo acionado podendo ser inclusão, alteração e cancelamento            OPERACIONAL                        NaN
PCLOGPEDIDOAPI   STATUS  VARCHAR2(1)                       Armazena os status do pedido, podendo ser aceito, rejeitado e processando            OPERACIONAL                        NaN
PCLOGPEDIDOAPI     JSON         CLOB                                    Armazena o objeto pedido de venda convertido em formato JSON            OPERACIONAL                        NaN
PCLOGPEDIDOAPI   CODCLI NUMBER(10,0)                                                                               Código do cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*