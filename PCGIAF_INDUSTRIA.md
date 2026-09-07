# 📊 Tabela: PCGIAF_INDUSTRIA

### Estrutura de Colunas e Restrições

          Tabela                         Coluna Tipo/Tamanho                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_INDUSTRIA          CODAPURGIAF_INDUSTRIA       NUMBER                                                                              Código Apuração GIAF Indutria    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_INDUSTRIA                      CODFILIAL  VARCHAR2(2)                                                                                           Código da Filial            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA                    DATA_INICIO         DATE                                                                                 Data de Inicio da Apuração            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA                   DATA_TERMINO         DATE                                                                                Data de Termino da Apuração            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA                IND_SUBAPURACAO  VARCHAR2(2)                                                                                  Indicador de Sub-apuração            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA               PERC_CRED_PRESUM NUMBER(12,4)                                                                            Percentual de Crédito Presumido            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA              VL_SAIDAS_N_INCEN NUMBER(18,6)                                                                              Saídas Não Incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA                VL_SAIDAS_INCEN NUMBER(18,6)                                                                                  Saídas Incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA       VL_SAIDAS_INCEN_FORA_NOR NUMBER(18,6)                                                            Saídas Incentivadas de PI para fora do Nordeste            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA       VL_SALDO_DEV_ANTES_INCEN NUMBER(18,6)                                                      Saldo Devedor do ICMS antes das Deduções do Incentivo            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA       VL_SALDO_DEV_FAIXA_INCEN NUMBER(18,6)                                                   Saldo Devedor do ICMS relativo à faixa incentivada de PI            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA  VL_CRED_PRESUM_SAI_INCEN_FORA NUMBER(18,6)                                      Crédito Presumido nas Saídas Incentivadas de PI para fora do Nordeste            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA VL_SALDO_DEV_FAI_INC_CRED_FORA NUMBER(18,6) Saldo Devedor relativo à faixa Incentivada de PI após o Crédito Presumido nas Saídas para fora do Nordeste            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA                 VL_CRED_PRESUM NUMBER(18,6)                                                                                          Crédito Presumido            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA            VL_DED_INCEN_INDUST NUMBER(18,6)                                                      Dedução de Incentivo da Indústria (Crédito Presumido)            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA          VL_SALDO_DEV_APOS_DED NUMBER(18,6)                                                                        Saldo Devedor de ICMS após Deduções            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*