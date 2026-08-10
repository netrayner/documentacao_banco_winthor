# 📊 Tabela: PCNFENTFRETE

### Estrutura de Colunas e Restrições

      Tabela                       Coluna Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFENTFRETE                  NUMTRANSENT NUMBER(10,0)                                                 Número de transação de entrada.            OPERACIONAL                        NaN
PCNFENTFRETE                NUMTRANSENTNF NUMBER(10,0)                                  Número de transação de entrada da nota fiscal.            OPERACIONAL                        NaN
PCNFENTFRETE                      NUMNOTA NUMBER(10,0)                                                                 Número da nota.            OPERACIONAL                        NaN
PCNFENTFRETE                        SERIE  VARCHAR2(3)                                                                          Série.            OPERACIONAL                        NaN
PCNFENTFRETE                    VLTOTALNF NUMBER(12,2)                                                                  Valor da nota.            OPERACIONAL                        NaN
PCNFENTFRETE                 VLTOTALFRETE NUMBER(12,2)                                                           Valor total do frete.            OPERACIONAL                        NaN
PCNFENTFRETE                    CODROTINA VARCHAR2(40)                                                                         Rotina.            OPERACIONAL                        NaN
PCNFENTFRETE                    PESOFRETE NUMBER(18,6)                                                         Indica o peso do frete.            OPERACIONAL                        NaN
PCNFENTFRETE                   VLTOTALIPI NUMBER(18,6) Valor total do IPI de todas as notas fiscais que compõe o conhecimento de frete            OPERACIONAL                        NaN
PCNFENTFRETE                    CODFORNEC  NUMBER(6,0) Valor total do IPI de todas as notas fiscais que compõe o conhecimento de frete            OPERACIONAL                        NaN
PCNFENTFRETE      CALCICMSFRETEFOBCSTPROD  VARCHAR2(1)                                                              CST ICMS Frete FOB            OPERACIONAL                        NaN
PCNFENTFRETE CALCPISCOFINSFRETEFOBCSTPROD  VARCHAR2(1)                                                        CST PIS/COFINS Frete FOB            OPERACIONAL                        NaN
PCNFENTFRETE                      CODCONT NUMBER(10,0)                                            Código conta de Frete FOB/NF Serviço            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*