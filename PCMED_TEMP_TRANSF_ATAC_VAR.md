# 📊 Tabela: PCMED_TEMP_TRANSF_ATAC_VAR

### Estrutura de Colunas e Restrições

                    Tabela                      Coluna   Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_TEMP_TRANSF_ATAC_VAR                 CODFILIAL_O    VARCHAR2(2)                     Código Filia Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR           CODFILIALRETIRA_O    VARCHAR2(2)                 Código da Filial Retira            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   CODPROD_O    NUMBER(6,0)                   Código Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 DESCRICAO_O   VARCHAR2(40)                Descrição Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  CODMARCA_O    NUMBER(8,0)                     Código Marca Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     MARCA_O   VARCHAR2(40)                            Marca Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTUNITCX_O   NUMBER(22,6)             Qtde. Unidades Caixa Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   QTD_EST_O   NUMBER(22,8)                          Estoque Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              QTD_SUGERIDA_O   NUMBER(22,6)                   Qtde. Sugerida Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR            QTD_TRANSFERIR_O   NUMBER(22,6)                 Qtde. Transferir Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 CODFILIAL_D    VARCHAR2(2)                   Código Filial Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                PRIORIDADE_D    NUMBER(6,0)                 Prioridade de Reposição            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   CODPROD_D    NUMBER(6,0)                  Código Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 DESCRICAO_D   VARCHAR2(40)               Descrição Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              TIPOSUGESTAO_D    VARCHAR2(2)                Tipo de Sugestão Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR          DESCTIPOSUGESTAO_D   VARCHAR2(40)             Descrição Tipo Sug. Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                ESTOQUEMIN_D   NUMBER(22,8)                  Estoque Minimo Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                ESTOQUEMAX_D   NUMBER(22,8)                  Estoque Máximo Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTESTGER_D   NUMBER(22,8)               Estoque Gerencial Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTPEDIDA_D   NUMBER(22,6)                  Qtde. Pendente Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              QTD_TRANSITO_D   NUMBER(22,6)                Estoque Trânsito Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR         QTD_BLOQSEMAVARIA_D   NUMBER(22,6)           Qt. Bloqueda sem Avaria Dest.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    CLASSE_D    VARCHAR2(1)                   Classe de Venda Dest.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                       PMC_D   NUMBER(22,6)                             PMC Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR               CUSTOULTENT_D   NUMBER(22,6)                Custo Ult. Entrada Dest.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    PVENDA_D   NUMBER(22,6)                     Preço Venda Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR            SUG_FRACIONADA_D   NUMBER(22,6)             Sugestão Fracionada Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTUNITCX_D   NUMBER(22,6)            Qtde. Unidades Caixa Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR             PERCARREDONDA_D   NUMBER(10,2)         Percentual Arredondamento Dest.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              QTD_SUGERIDA_D   NUMBER(22,6)                  Qtde. Sugerida Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR            QTD_TRANSFERIR_D   NUMBER(22,6)                Qtde. Transferir Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR            VLR_TRANSFERIR_D   NUMBER(22,6)                Valor Transferir Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   CODEQUIPE    VARCHAR2(4)                        Código da Equipe            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                CODCATEGORIA    NUMBER(6,0)                          Cód. Categoria            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                      CODSEC    NUMBER(6,0)                              Cód. Seção            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     CODEPTO    NUMBER(6,0)                             Cód. Depto.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   CODFORNEC    NUMBER(6,0)                         Cód. Fornecedor            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   EMBALAGEM   VARCHAR2(12)                               Embalagem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     UNIDADE    VARCHAR2(2)                           Unidade Venda            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  TRIBUTACAO    VARCHAR2(1)                         Flag Tributação            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                       CODST    NUMBER(4,0)                       Código Tributação            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 QTVENDMES_D   NUMBER(16,3)                 Qtde. Venda Mês Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                QTVENDMES1_D   NUMBER(16,3)               Qtde. Venda Mês 1 Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                QTVENDMES2_D   NUMBER(16,3)               Qtde. Venda Mês 2 Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                QTVENDMES3_D   NUMBER(16,3)               Qtde. Venda Mês 3 Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                QTPENDENTE_D   NUMBER(16,3)                  Qtde. Pendente Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    CODFAB_O   VARCHAR2(30)                   Código Fábrica Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    CODFAB_D   VARCHAR2(30)                  Código Fábrica Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR               CODAUXILIAR_O   NUMBER(20,0)                              EAN Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR               CODAUXILIAR_D   NUMBER(20,0)                             EAN Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     QUEBRA1   VARCHAR2(20)                Valor da primeira quebra            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     QUEBRA2   VARCHAR2(20)                 Valor da segunda quebra            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     QUEBRA3   VARCHAR2(20)                Valor da terceira quebra            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     QUEBRA4   VARCHAR2(20)                  Valor da quarta quebra            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                      NUMPED   NUMBER(11,0)                           Pedido Gerado            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                       QTPED   NUMBER(22,6)                     Qtde. Pedido Gerado            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTFALTAPED   NUMBER(22,6)                      Qtde. Falta Pedido            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                      CODCLI    NUMBER(6,0)                       Código do Cliente            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR         NOMEFANTASIACLIENTE   VARCHAR2(40)                Nome Fantasia do Cliente            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 QTGIRODIA_D   NUMBER(16,3)                      Giro Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 QTDIASREP_D    NUMBER(9,0)                 Cobertura Prod. Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR   DESCCONSIDERAESTPENDSUG_D    VARCHAR2(3)        Flag Desconsiderar Est. Pendente            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              PRAZOENTREGA_O    NUMBER(4,0)                    Prazo Entrega Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR             PERCARREDONDA_O   NUMBER(10,2)        Percentual Arredondamento Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR       CXFORNEC_TRANSFERIR_O   NUMBER(22,6)              Caixas para Transf. Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR            TIPO_SUG_LOJA_CD    VARCHAR2(1)                Tipo Sugestão Loja ou CD            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR      TIPO_SUG_COMPRA_TRANSF    VARCHAR2(1)         Tipo Sugestão Compra ou Transf.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR DESC_TIPO_SUG_COMPRA_TRANSF   VARCHAR2(15)   Descrição Tipo Sug. Compra ou Transf.            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR         CODFORNECPRIORIDADE    NUMBER(6,0)              Cód. Fornecedor Prioridade            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR       DESC_FORNECPRIORIDADE   VARCHAR2(50)            Descrição Fornec. Prioridade            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR    CODDESC_FORNECPRIORIDADE   VARCHAR2(60)     Cód. e Descrição Fornec. Prioridade            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 NUMSUGESTAO   NUMBER(10,0)                      Sugestão de Compra            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR               QTSUGCOMPRA_D   NUMBER(22,6)               Qtde. Sug. Compra Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                  QTIMPORT_D   NUMBER(22,6)                Qtde. Importação Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR        EMB_POR_FORNECEDOR_O    VARCHAR2(1)                Flag Emb. Fornec. Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              PRECO_TRANSF_O   NUMBER(22,6)                    Preço Transf. Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    PRECOPED   NUMBER(22,6)                            Preço Pedido            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR          OBSERVACAOREJEICAO  VARCHAR2(240)                     Observação Rejeição            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                   DTGERACAO           DATE                            Data Geração            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR          CODPROD_TRANSITO_O    NUMBER(6,0)              Cód. Prod. Trânsito Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR        DESCRICAO_TRANSITO_O   VARCHAR2(40)              Descrição Trânsito Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              NUMSUGESTAOREP   NUMBER(12,0)                      Sugestão Reposição            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 INTEGRADORA    NUMBER(6,0)                   Código da Integradora            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR             NOMEINTEGRADORA   VARCHAR2(60)                     Nome da Integradora            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 QTOPERLOG_O   NUMBER(22,6)        Qtde. Operador Logístico Destino            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 QTOPERLOG_D   NUMBER(22,6)         Qtde. Operador Logístico Origem            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR        INTEGRADORAESPELHONF    NUMBER(6,0)           Código Integradora Espelho NF            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR    NOMEINTEGRADORAESPELHONF   VARCHAR2(60)             Nome Integradora Espelho NF            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                 INFOQUEBRAS  VARCHAR2(100)                 Informações das quebras            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                    ESTMIN_O         NUMBER                 Estoque Minimo da PCEST            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                ESTOQUEMIN_O         NUMBER          Estoque Minimo da PCPRODFILIAL            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR             ESTOQUEMINSUG_O         NUMBER     Estoque Minimo Aplicado na Sugestao            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     FORMULA    VARCHAR2(1)                   Se existe Formuma S/N            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR       FORMULA_QT_SUGERIDA_D VARCHAR2(4000)                        Formula aplicada            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR             TIPOCUSTOTRANSF    VARCHAR2(2)                Tipo Custo Transferencia            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR       QTCANCESTOQUEMINSUG_O         NUMBER Qtde Cancelada por estoque insuficiente            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                     NUMLOTE   VARCHAR2(15)                          Numero do Lote            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR              ESTOQUEPORLOTE    VARCHAR2(1)                        Estoque por Lote            OPERACIONAL                        NaN
PCMED_TEMP_TRANSF_ATAC_VAR                PEDIDOAVARIA    VARCHAR2(1)                           Pedido Avaria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*