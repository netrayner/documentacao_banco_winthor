# 📊 Tabela: PCCOBCARTAOFILIAL

### Estrutura de Colunas e Restrições

           Tabela                     Coluna Tipo/Tamanho                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOBCARTAOFILIAL                  CODFILIAL  VARCHAR2(2)                                                                                                                     Código da filial.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL                     CODCOB  VARCHAR2(4)                                                                                                                   Código de cobrança.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL              PERCTXADMINCC  NUMBER(5,2)                                                                                                      Táxa de administração do cartão.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL                 QTPARCELAS  NUMBER(4,0)                                                                                          Quantidade de parcelas do cartão de crédito.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL        FAIXAINIQTPARCTXADM  NUMBER(4,0)                    FAIXA INICIAL DE PASRCELAS PARA IDENTIFICAÇÃO DA TAXA DE ADMINISTRAÇÃO A SER UTILIZADA, NO FECHAMENTO DO CHECKOUT.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL        FAIXAFIMQTPARCTXADM  NUMBER(4,0)                      FAIXA FINAL DE PASRCELAS PARA IDENTIFICAÇÃO DA TAXA DE ADMINISTRAÇÃO A SER UTILIZADA, NO FECHAMENTO DO CHECKOUT.            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL      PARCELAUNICAOPERADORA  VARCHAR2(1)                                                                                            Gerar única parcela a receber da operadora            OPERACIONAL                        NaN
PCCOBCARTAOFILIAL GERARPARCELAUNICARECEBEDOR  VARCHAR2(1) Quando a cobrança for cartão de crédito, deve ser possível definir se deve ser gerado somente uma única parcela a receber da operador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*