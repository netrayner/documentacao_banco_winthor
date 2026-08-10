# 📊 Tabela: PCPEDIDOTEMPORARIO

### Estrutura de Colunas e Restrições

            Tabela  Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDOTEMPORARIO      ID NUMBER(10,0)           Define o ID do pedido temporário    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIDOTEMPORARIO    DATA         DATE                  Data do pedido temporário            OPERACIONAL                        NaN
PCPEDIDOTEMPORARIO  NUMPED NUMBER(10,0)       Define o número do pedido temporário            OPERACIONAL                        NaN
PCPEDIDOTEMPORARIO CODUSUR NUMBER(10,0)          Define o RCA do pedido temporário            OPERACIONAL                        NaN
PCPEDIDOTEMPORARIO    JSON         CLOB Define o arquivo json do pedido temporário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*