# 📊 Tabela: PCSUGALTCOMISSAOI

### Estrutura de Colunas e Restrições

           Tabela        Coluna Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGALTCOMISSAOI  CODALTERACAO NUMBER(10,0)                                                               Indica o código da alteração de sugestão gerada.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGALTCOMISSAOI       CODPROD  NUMBER(6,0)                                         Indica o código do produto para a sugestão de alteração para comissão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGALTCOMISSAOI     PERCOMRCA  NUMBER(8,4)      Indica o percentual de comissão por produto do RCA da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI PERCOMRCANOVO  NUMBER(8,4) Indica o novo percentual de comissão por produto do RCA da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI            QT NUMBER(18,6)                          Indica a quantidade do produto na nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI         PUNIT NUMBER(18,6)                      Indica o valor unitário do produto na nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI     PERCLUCRO  NUMBER(8,4)                Indica o percentual de lucro por produto da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI   VALORDIFRCA NUMBER(18,6)                  Indica o valor da diferença por produto referente à sugestão de alteração na comissão do RCA.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI     PERCOMMOT  NUMBER(8,4)    Indica o percentual de comissão do motorista do item da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI PERCOMMOTNOVO  NUMBER(8,4)       Indica o novo percentual de comissão do Motorista da nota fiscal da sugestão de alteração para comissão.            OPERACIONAL                        NaN
PCSUGALTCOMISSAOI   VALORDIFMOT NUMBER(18,6)            Indica o valor da diferença por produto referente à sugestão de alteração na comissão do motorista.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*