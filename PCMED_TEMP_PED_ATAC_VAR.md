# 📊 Tabela: PCMED_TEMP_PED_ATAC_VAR

### Estrutura de Colunas e Restrições

                 Tabela                 Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_TEMP_PED_ATAC_VAR            CODFILIAL_O  VARCHAR2(2)             Código Filia Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR      CODFILIALRETIRA_O  VARCHAR2(2)         Código da Filial Retira            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR              CODPROD_O  NUMBER(6,0)           Código Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR            CODFILIAL_D  VARCHAR2(2)           Código Filial Destino            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR              CODPROD_D  NUMBER(6,0)          Código Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR              DTGERACAO         DATE                    Data Geração            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR            DESCRICAO_O VARCHAR2(40)        Descrição Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR       QTD_TRANSFERIR_O NUMBER(22,6)         Qtde. Transferir Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR              QTD_EST_O NUMBER(22,8)                  Estoque Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR         PRECO_TRANSF_O NUMBER(22,6)            Preço Transf. Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR    CODFORNECPRIORIDADE  NUMBER(6,0)      Cód. Fornecedor Prioridade            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR TIPO_SUG_COMPRA_TRANSF  VARCHAR2(1) Tipo Sugestão Compra ou Transf.            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR                QUEBRA1 VARCHAR2(20)        Valor da primeira quebra            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR                QUEBRA2 VARCHAR2(20)         Valor da segunda quebra            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR                QUEBRA3 VARCHAR2(20)        Valor da terceira quebra            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR                QUEBRA4 VARCHAR2(20)          Valor da quarta quebra            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR               SEQFALTA  NUMBER(9,0)              Sequência de Falta            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR            INTEGRADORA  NUMBER(6,0)           Código da Integradora            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR   INTEGRADORAESPELHONF  NUMBER(6,0)   Código Integradora Espelho NF            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR             QTUNITCX_D NUMBER(22,6)    Qtde. Unidades Caixa Destino            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR          CODAUXILIAR_O NUMBER(20,0)                      EAN Origem            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR                NUMLOTE VARCHAR2(15)                  Numero do Lote            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR         ESTOQUEPORLOTE  VARCHAR2(1)                Estoque por Lote            OPERACIONAL                        NaN
PCMED_TEMP_PED_ATAC_VAR           PEDIDOAVARIA  VARCHAR2(1)                   Pedido Avaria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*