# 📊 Tabela: PCPEDGERABONIF

### Estrutura de Colunas e Restrições

        Tabela         Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDGERABONIF         NUMPED NUMBER(10,0)  Número do pedido de entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDGERABONIF        CODPROD  NUMBER(6,0) Código do produto bonificado.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDGERABONIF           QTDE NUMBER(20,6)        Quantidade bonificada.            OPERACIONAL                        NaN
PCPEDGERABONIF        VLPRECO NUMBER(18,6)  Preço do produto bonificado.            OPERACIONAL                        NaN
PCPEDGERABONIF CODPRODBONIFIC  NUMBER(6,0)                           NaN    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*