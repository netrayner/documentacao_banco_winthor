# 📊 Tabela: PC_LOG_CONFIG_1249

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PC_LOG_CONFIG_1249         CODUSUR       NUMBER                                 CODIGO DO USUARIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249           DTLOG         DATE                      DATA DA INCLUSAO DO REGISTRO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249          ROTINA VARCHAR2(40)                                  NUMERO DA ROTINA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249    TIPO_PERIODO  VARCHAR2(1)                                      TIPO PERIODO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249 DT_TIPO_PERIODO         DATE                                   DATA DO PERIODO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249        TIPO_RCA  VARCHAR2(1)                                          TIPO RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249             RCA  VARCHAR2(1)                                               RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249    ORIGEM_VENDA  VARCHAR2(1)                                      ORIGEM VENDA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249  TIPO_RELATORIO  VARCHAR2(1)                                    TIPO RELATORIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   TIPO_CALC_COM  VARCHAR2(1)                                  CALCULO COMISSAO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   TIPO_VL_RECEB  VARCHAR2(1)                                    VALOR RECEBIDO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249  IMP_VL_DEV_EST  VARCHAR2(1) IMPRIMIR VALOR DEDUÇAO SO COM ESTORNO DE COMISSAO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   DED_VL_O_DESP  VARCHAR2(1)                     DEDUZIR VALOR OUTRAS DESPESAS            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249    DED_VL_FRETE  VARCHAR2(1)                           DESDUZIR VALOR DO FRETE            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249 OB_TIPO_COM_COB  VARCHAR2(1)             OBEDECER TIPO DA COMISSAO DA COBRANÇA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249    COMISSAO_RAT  VARCHAR2(1)                                  COMISSAO RATEADA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249     RCA_COM_MOV  VARCHAR2(1)                  RCAS COM MOVIMENTAÇAO NO PERIODO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249 OB_TIPO_CAD_RCA  VARCHAR2(1)            OBEDECER TIPO COMISSAO DO CADASTRO RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249     IMP_RCA_MOV  VARCHAR2(1)                        IMPRIMIR SOMENTE RCA ATIVO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   IMP_SUP_ATIVO  VARCHAR2(1)                         IMPRIMIR SUPERVISOR ATIVO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249     INC_DEV_TV8  VARCHAR2(1)                         INCLUIR DEVOLUÇOES DE TV8            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   COM_PROG_DESC  VARCHAR2(1)                        COMPRA PROG. POR DESCRIÇAO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249   ORDEM_CLIENTE  VARCHAR2(1)                                     ORDEM CLIENTE            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249       ORDEM_RCA  VARCHAR2(1)                                         ORDEM RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1249         EMISSAO  VARCHAR2(1)                                           EMISSAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*