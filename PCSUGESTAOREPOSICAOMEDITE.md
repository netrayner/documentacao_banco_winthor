# 📊 Tabela: PCSUGESTAOREPOSICAOMEDITE

### Estrutura de Colunas e Restrições

                   Tabela                      Coluna   Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGESTAOREPOSICAOMEDITE              NUMSUGESTAOREP   NUMBER(12,0)                      Número da Sugestão    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDITE                 CODFILIAL_O    VARCHAR2(2)                     Código Filia Origem    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDITE                   CODPROD_O    NUMBER(6,0)                   Código Produto Origem    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDITE                 CODFILIAL_D    VARCHAR2(2)                   Código Filial Destino    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDITE                   CODPROD_D    NUMBER(6,0)                  Código Produto Destino    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDITE                  CODMARCA_O    NUMBER(8,0)                     Código Marca Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTUNITCX_O   NUMBER(22,6)             Qtde. Unidades Caixa Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                   QTD_EST_O   NUMBER(22,8)                          Estoque Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              QTD_SUGERIDA_O   NUMBER(22,6)                   Qtde. Sugerida Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE            QTD_TRANSFERIR_O   NUMBER(22,6)                 Qtde. Transferir Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                PRIORIDADE_D    NUMBER(6,0)                 Prioridade de Reposição            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              TIPOSUGESTAO_D    VARCHAR2(2)                Tipo de Sugestão Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE          DESCTIPOSUGESTAO_D   VARCHAR2(40)             Descrição Tipo Sug. Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                ESTOQUEMIN_D   NUMBER(22,8)                  Estoque Minimo Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                ESTOQUEMAX_D   NUMBER(22,8)                  Estoque Máximo Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTESTGER_D   NUMBER(22,8)               Estoque Gerencial Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTPEDIDA_D   NUMBER(22,6)                  Qtde. Pendente Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              QTD_TRANSITO_D   NUMBER(22,6)                Estoque Trânsito Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE         QTD_BLOQSEMAVARIA_D   NUMBER(22,6)           Qt. Bloqueda sem Avaria Dest.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    CLASSE_D    VARCHAR2(1)                   Classe de Venda Dest.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                       PMC_D   NUMBER(22,6)                             PMC Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE               CUSTOULTENT_D   NUMBER(22,6)                Custo Ult. Entrada Dest.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    PVENDA_D   NUMBER(22,6)                     Preço Venda Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE            SUG_FRACIONADA_D   NUMBER(22,6)             Sugestão Fracionada Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTUNITCX_D   NUMBER(22,6)            Qtde. Unidades Caixa Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE             PERCARREDONDA_D   NUMBER(10,2)         Percentual Arredondamento Dest.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              QTD_SUGERIDA_D   NUMBER(22,6)                  Qtde. Sugerida Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE            QTD_TRANSFERIR_D   NUMBER(22,6)                Qtde. Transferir Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE            VLR_TRANSFERIR_D   NUMBER(22,6)                Valor Transferir Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                   CODEQUIPE    VARCHAR2(4)                        Código da Equipe            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                CODCATEGORIA    NUMBER(6,0)                          Cód. Categoria            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                      CODSEC    NUMBER(6,0)                              Cód. Seção            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     CODEPTO    NUMBER(6,0)                             Cód. Depto.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                   CODFORNEC    NUMBER(6,0)                         Cód. Fornecedor            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                   EMBALAGEM   VARCHAR2(12)                               Embalagem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     UNIDADE    VARCHAR2(2)                           Unidade Venda            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  TRIBUTACAO    VARCHAR2(1)                         Flag Tributação            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                       CODST    NUMBER(4,0)                       Código Tributação            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 QTVENDMES_D   NUMBER(16,3)                 Qtde. Venda Mês Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                QTVENDMES1_D   NUMBER(16,3)               Qtde. Venda Mês 1 Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                QTVENDMES2_D   NUMBER(16,3)               Qtde. Venda Mês 2 Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                QTVENDMES3_D   NUMBER(16,3)               Qtde. Venda Mês 3 Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                QTPENDENTE_D   NUMBER(16,3)                  Qtde. Pendente Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    CODFAB_O   VARCHAR2(30)                   Código Fábrica Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    CODFAB_D   VARCHAR2(30)                  Código Fábrica Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE               CODAUXILIAR_O   NUMBER(20,0)                              EAN Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE               CODAUXILIAR_D   NUMBER(20,0)                             EAN Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     QUEBRA1   VARCHAR2(20)                Valor da primeira quebra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     QUEBRA2   VARCHAR2(20)                 Valor da segunda quebra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     QUEBRA3   VARCHAR2(20)                Valor da terceira quebra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     QUEBRA4   VARCHAR2(20)                  Valor da quarta quebra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                      NUMPED   NUMBER(11,0)                           Pedido Gerado            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                       QTPED   NUMBER(22,6)                     Qtde. Pedido Gerado            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTFALTAPED   NUMBER(22,6)                      Qtde. Falta Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                      CODCLI    NUMBER(6,0)                       Código do Cliente            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 QTGIRODIA_D   NUMBER(16,3)                      Giro Prod. Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 QTDIASREP_D    NUMBER(9,0)                 Cobertura Prod. Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE   DESCCONSIDERAESTPENDSUG_D    VARCHAR2(3)        Flag Desconsiderar Est. Pendente            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              PRAZOENTREGA_O    NUMBER(4,0)                    Prazo Entrega Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE             PERCARREDONDA_O   NUMBER(10,2)        Percentual Arredondamento Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE       CXFORNEC_TRANSFERIR_O   NUMBER(22,6)              Caixas para Transf. Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE            TIPO_SUG_LOJA_CD    VARCHAR2(1)                Tipo Sugestão Loja ou CD            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE      TIPO_SUG_COMPRA_TRANSF    VARCHAR2(1)         Tipo Sugestão Compra ou Transf.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE DESC_TIPO_SUG_COMPRA_TRANSF   VARCHAR2(15)   Descrição Tipo Sug. Compra ou Transf.            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE         CODFORNECPRIORIDADE    NUMBER(6,0)              Cód. Fornecedor Prioridade            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE    CODDESC_FORNECPRIORIDADE   VARCHAR2(60)            Descrição Fornec. Prioridade            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 NUMSUGESTAO   NUMBER(10,0)                      Sugestão de Compra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE               QTSUGCOMPRA_D   NUMBER(22,6)               Qtde. Sug. Compra Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                  QTIMPORT_D   NUMBER(22,6)                Qtde. Importação Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE        EMB_POR_FORNECEDOR_O    VARCHAR2(1)                Flag Emb. Fornec. Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE              PRECO_TRANSF_O   NUMBER(22,6)                    Preço Transf. Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE          OBSERVACAOREJEICAO  VARCHAR2(240)                     Observação Rejeição            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    PRECOPED   NUMBER(22,6)                            Preço Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE          CODPROD_TRANSITO_O    NUMBER(6,0)              Cód. Prod. Trânsito Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 INTEGRADORA    NUMBER(6,0)                   Código da Integradora            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 QTOPERLOG_D   NUMBER(22,6)         Qtde. Operador Logístico Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 QTOPERLOG_O   NUMBER(22,6)        Qtde. Operador Logístico Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE             NOMEINTEGRADORA   VARCHAR2(60)                        Nome Integradora            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE        INTEGRADORAESPELHONF    NUMBER(6,0)           Código Integradora Espelho NF            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE    NOMEINTEGRADORAESPELHONF   VARCHAR2(60)             Nome Integradora Espelho NF            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                 INFOQUEBRAS  VARCHAR2(100)                 Informações das quebras            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE           CODFILIALRETIRA_O    VARCHAR2(2)                 Código da Filial Retira            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                    ESTMIN_O   NUMBER(22,8)                 Estoque Minimo da PCEST            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                ESTOQUEMIN_O   NUMBER(22,8)          Estoque Minimo da PCPRODFILIAL            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE             ESTOQUEMINSUG_O   NUMBER(22,8)     Estoque Minimo Aplicado na Sugestao            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE                     FORMULA    VARCHAR2(1)                   Se existe Formuma S/N            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE       FORMULA_QT_SUGERIDA_D VARCHAR2(4000)                        Formula aplicada            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE             TIPOCUSTOTRANSF    VARCHAR2(2)                Tipo Custo Transferencia            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDITE       QTCANCESTOQUEMINSUG_O   NUMBER(22,8) Qtde Cancelada por estoque insuficiente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*