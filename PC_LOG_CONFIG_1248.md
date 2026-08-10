# 📊 Tabela: PC_LOG_CONFIG_1248

### Estrutura de Colunas e Restrições

            Tabela           Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PC_LOG_CONFIG_1248          CODUSUR       NUMBER                                   CODIGO DO USUARIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248            DTLOG         DATE                        DATA DA INCLUSAO DO REGISTRO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248           ROTINA VARCHAR2(40)                                    NUMERO DA ROTINA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248     TIPO_PERIODO  VARCHAR2(1)                                        TIPO PERIODO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248    CALC_COMISSAO  VARCHAR2(1)                                       CAL. COMISSAO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248         CRITERIO  VARCHAR2(1)                                            CRITERIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248         TIPO_RCA  VARCHAR2(1)                                            TIPO RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248   VALOR_RECEBIDO  VARCHAR2(1)                                      VALOR RECEBIDO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248   TIPO_RELATORIO  VARCHAR2(1)                                   TIPO DO RELATORIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  TIPO_RELATORIO2  VARCHAR2(1)                                  TIPO  DO RELATORIO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  OB_TIPO_COM_COB  VARCHAR2(1)               OBEDECER TIPO DE COMISSAO DA COBRANÇA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248    CONS_ICMS_RET  VARCHAR2(1)                              CONSIDERAR ICMS RETIDO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248 DED_CRED_CLIENTE  VARCHAR2(1) DEDUZIR CREDITO DE CLIENTE PROVENIENTE DE DEVOLUÇÃO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  NAO_IMPRIM_PERC  VARCHAR2(1)                             NÃO IMPRIMIR % COMISSAO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  IMPRIM_REC_PGTO  VARCHAR2(1)                           IMPRIMIR RECIBO PAGAMENTO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  NAO_IMPRIM_VALE  VARCHAR2(1)                                  NÃO IMPRIMIR VALES            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248   EMAIL_PARA_RCA  VARCHAR2(1)                                      EMAIL PARA RCA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248 NAO_IMP_RES_INAD  VARCHAR2(1)                   NÃO IMPRIMIR RESUMO INADIMPLENCIA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  CONS_VL_EST_TIT  VARCHAR2(1)                CONSIDERAR VALOR ESTORNADO DO TITULO            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248  EMIT_TIT_COM_PG  VARCHAR2(1)                    EMITIR TITULOS COM COMISSAO PAGA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248   IMP_NUM_DUPLIC  VARCHAR2(1)                               IMPRIMIR Nº DUPLICATA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248     COMISSAO_RAT  VARCHAR2(1)                                    COMISSÃO RATEADA            OPERACIONAL                        NaN
PC_LOG_CONFIG_1248 IMP_COM_TIT_N_PG  VARCHAR2(1)    IMPRIMIR COMISSAO A RECEBER DE TITULOS NÃO PAGOS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*