# 📊 Tabela: PCPEDISELO

### Estrutura de Colunas e Restrições

    Tabela  Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDISELO CODGUIA VARCHAR2(14)              Número da guia referente a movimentação            OPERACIONAL                        NaN
PCPEDISELO  NUMPED NUMBER(10,0) Número do pedido de venda que utiliza a guia do selo            OPERACIONAL                        NaN
PCPEDISELO QTSAIDA NUMBER(10,0)             Qtd. De selos utilizados na movimentação            OPERACIONAL                        NaN
PCPEDISELO CODPROD NUMBER(10,0)             Cód. Produto que utilizou a guia de selo            OPERACIONAL                        NaN
PCPEDISELO  NUMSEQ NUMBER(10,0)      Nº. De sequencia da digitação do item do pedido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*