# 📊 Tabela: PCGIAF_DISTRIBUICAO

### Estrutura de Colunas e Restrições

             Tabela                   Coluna Tipo/Tamanho                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_DISTRIBUICAO CODAPURGIAF_DISTRIBUICAO       NUMBER                                              Código da Apuração do GIAF para a Distribuição    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_DISTRIBUICAO                CODFILIAL  VARCHAR2(2)                                                                            Código da Filial            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO              DATA_INICIO         DATE                                                                  Data de Inicio da Apuração            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO             DATA_TERMINO         DATE                                                                 Data de Termino da Apuração            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO          IND_SUBAPURACAO  VARCHAR2(2)                                                                   Indicador de Sub-apuração            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO            PERC_ENTRADAS NUMBER(18,6)                                                  G4_01 - Entradas (percentual de incentivo)            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO     VL_ENTRADAS_N_INC_PI NUMBER(18,6)                                                     G4_02 - Entradas não incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO       VL_ENTRADAS_INC_PI NUMBER(18,6)                                                         G4_03 - Entradas incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO              PERC_SAIDAS NUMBER(18,6)                                                    G4_04 - Saídas (percentual de incentivo)            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO       VL_SAIDAS_N_INC_PI NUMBER(18,6)                                                       G4_05 - Saídas não incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO         VL_SAIDAS_INC_PI NUMBER(18,6)                                                           G4_06 - Saídas incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO VL_SALDO_DEV_ANT_DED_INC NUMBER(18,6) G4_07 - Saldo devedor do ICMS antes das deduções do incentivo (PI e itens não incentivados)            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO      VL_CRED_PRE_ENT_INC NUMBER(18,6)                                   G4_08 - Crédito presumido nas entradas incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO      VL_CRED_PRE_SAI_INC NUMBER(18,6)                                     G4_09 - Crédito presumido nas saídas incentivadas de PI            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO       VL_DED_INC_CEN_DIS NUMBER(18,6)                   G4_10 - Dedução de incentivo da Central de Distribuição (entradas/saídas)            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO   VL_SALDO_DE_AP_DED_INC NUMBER(18,6)                                    G4_11 - Saldo devedor do ICMS após deduções do incentivo            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO          IND_REC_CEN_DIS NUMBER(18,6)                                   G4_12 - Índice de recolhimento da central de distribuição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*