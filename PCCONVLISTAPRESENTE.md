# 📊 Tabela: PCCONVLISTAPRESENTE

### Estrutura de Colunas e Restrições

             Tabela             Coluna   Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONVLISTAPRESENTE           NUMLISTA    NUMBER(6,0)                                         Número de Identificação da Lista            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE         DATACOMPRA           DATE                                                           Data da Compra            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE             CODCLI    NUMBER(6,0)                                                        Código do Cliente            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE      NOMECONVIDADO  VARCHAR2(100)                                                           Nome Convidado            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE        CODAUXILIAR   NUMBER(16,0)                                              Código de barras do produto            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE               QTDE   NUMBER(10,2)                                                               Quantidade            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE             CODIGO   NUMBER(10,0)                                         Codigo sequencial dos convidados    CHAVE PRIMÁRIA (PK)                        NaN
PCCONVLISTAPRESENTE        BAIXAMANUAL    VARCHAR2(1)                                        Indicador de baixa manual do item            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE CODFUNCBAIXAMANUAL    NUMBER(6,0)                                    Codigo do funcionário que baixou item            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE           MENSAGEM VARCHAR2(4000)                                                       Mensagem Convidado            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE      NUMTRANSVENDA   NUMBER(10,0)                        Número da transação da venda, realizada pelo PDV.            OPERACIONAL                        NaN
PCCONVLISTAPRESENTE            NUMORCA   NUMBER(10,0) Número do orçamento para identificar de onde esse cliente baixou a venda            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*