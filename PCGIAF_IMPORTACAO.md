# 📊 Tabela: PCGIAF_IMPORTACAO

### Estrutura de Colunas e Restrições

           Tabela                     Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_IMPORTACAO     CODAPURGIAF_IMPORTACAO       NUMBER           Código da Apuração do GIAF para a Importação    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_IMPORTACAO                  CODFILIAL  VARCHAR2(2)                                       Código da Filial            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO                DATA_INICIO         DATE                             Data de Inicio da Apuração            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO               DATA_TERMINO         DATE                            Data de Termino da Apuração            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO            IND_SUBAPURACAO  VARCHAR2(2)                              Indicador de Sub-apuração            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO     VL_IMPORTACAO_ICMS_DIF NUMBER(18,6)                          Importações com ICMS diferido            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO       VL_ICMS_DIFERIDO_IMP NUMBER(18,6)                           ICMS diferido nas importaçõe            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO         VL_SAIDAS_N_INC_PI NUMBER(18,6)                          Saídas não incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO       PERC_INC_SAIDAS_FORA NUMBER(12,4) Percentual de incentivo nas saídas para fora do Estado            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO         VL_SAIDAS_INC_FORA NUMBER(18,6)          Saídas incentivadas de PI para fora do Estado            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO    VL_ICMS_SAIDAS_INC_FORA NUMBER(18,6) ICMS das saídas incentivadas de PI para fora do Estado            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO VL_CRED_PRESUM_SAIDAS_FORA NUMBER(18,6)       Crédito presumido nas saídas para fora do Estado            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO      VL_DED_INC_IMPORTACAO NUMBER(18,6) Dedução de incentivo da Importação (crédito presumido)            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO  VL_SALDO_DEV_ICMS_ANT_DED NUMBER(18,6)  Saldo devedor do ICMS antes das deduções do incentivo            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO VL_SALDO_DEV_ICMS_APOS_DED NUMBER(18,6)       Saldo devedor do ICMS após deduções do incentivo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*