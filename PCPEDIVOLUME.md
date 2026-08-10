# 📊 Tabela: PCPEDIVOLUME

### Estrutura de Colunas e Restrições

      Tabela        Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIVOLUME        NUMPED NUMBER(10,0)                        Numero do pedido            OPERACIONAL                        NaN
PCPEDIVOLUME        VOLUME  NUMBER(4,0)                          Volume montado            OPERACIONAL                        NaN
PCPEDIVOLUME       NUMNOTA NUMBER(10,0)      Numero da nota referente ao volume            OPERACIONAL                        NaN
PCPEDIVOLUME NUMTRANSVENDA NUMBER(10,0) Numero da transação referente ao volume            OPERACIONAL                        NaN
PCPEDIVOLUME   VOLUMECAIXA VARCHAR2(14)                 Volume da caixa montada            OPERACIONAL                        NaN
PCPEDIVOLUME      AGRUPADO  VARCHAR2(1)      Determina se o Volume foi agrupado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*