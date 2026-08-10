# 📊 Tabela: PCPRODUTOSCOTACOES

### Estrutura de Colunas e Restrições

            Tabela                Coluna Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOSCOTACOES             CODEDITAL  NUMBER(9,0)          Códigoedital.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOSCOTACOES               CODPROD  NUMBER(9,0)         CódigoProduto.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES                  LOTE VARCHAR2(10)                  Lote.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOSCOTACOES           NUMERO_ITEM  NUMBER(9,0)          Numerodoitem.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOSCOTACOES PERCENTUALBONIFICACAO NUMBER(18,6) Percentualbonificação.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES   PERCENTUALCOMERCIAL NUMBER(18,6)   Percentualcomercial.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES     PERCENTUALREPASSE NUMBER(18,6)     Percentualrepasse.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES            PRECOBRUTO NUMBER(18,6)            Preçobruto.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES   MIXPRECO_VENDA_INIC NUMBER(18,6)  Mixpreçovendainicial.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES    MIXPRECO_VENDA_MIN NUMBER(18,6)   Mixpreçovendaminimo.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES     MIXPERCENTUAL_IMP NUMBER(18,6) Mexpercentualimpostos.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES         PERCENTUALCAP NUMBER(18,6)         PercentualCAP.            OPERACIONAL                        NaN
PCPRODUTOSCOTACOES        PERCENTUALICMS NUMBER(18,6)        PercentualICMS.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*