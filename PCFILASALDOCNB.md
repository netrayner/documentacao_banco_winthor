# 📊 Tabela: PCFILASALDOCNB

### Estrutura de Colunas e Restrições

        Tabela                   Coluna  Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILASALDOCNB                   CODIGO  NUMBER(20,0)                                                    Chave tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCFILASALDOCNB                CODFILIAL   VARCHAR2(2)                                                   Código filial            OPERACIONAL                        NaN
PCFILASALDOCNB            CODPLANOCONTA   NUMBER(5,0)                                           Código plano de conta            OPERACIONAL                        NaN
PCFILASALDOCNB                      MES   NUMBER(2,0)                                                    Mês do saldo            OPERACIONAL                        NaN
PCFILASALDOCNB                      ANO   NUMBER(4,0)                                                    Ano do saldo            OPERACIONAL                        NaN
PCFILASALDOCNB           CODREDUZIDO_PC  VARCHAR2(12)                                        Código reduzido da conta            OPERACIONAL                        NaN
PCFILASALDOCNB              CODCONTA_PC  VARCHAR2(40)                                       Código análitico da conta            OPERACIONAL                        NaN
PCFILASALDOCNB              VALORDEBITO  NUMBER(22,2)                                                    Valor debito            OPERACIONAL                        NaN
PCFILASALDOCNB             VALORCREDITO  NUMBER(22,2)                                                   Valor credito            OPERACIONAL                        NaN
PCFILASALDOCNB       VLRDEBENCERRAMENTO  NUMBER(22,2)                                    Valor debito de encerramento            OPERACIONAL                        NaN
PCFILASALDOCNB       VLRCREENCERRAMENTO  NUMBER(22,2)                                   Valor credito de encerramento            OPERACIONAL                        NaN
PCFILASALDOCNB             VLRDEBCONCIL  NUMBER(22,2)                                         Valor debito conciliado            OPERACIONAL                        NaN
PCFILASALDOCNB             VLRCRECONCIL  NUMBER(22,2)                                        Valor credito conciliado            OPERACIONAL                        NaN
PCFILASALDOCNB VLRDEBCONCILENCERRAMENTO  NUMBER(22,2)                         Valor debito conciliado de encerramento            OPERACIONAL                        NaN
PCFILASALDOCNB VLRCRECONCILENCERRAMENTO  NUMBER(22,2)                        Valor credito conciliado de encerramento            OPERACIONAL                        NaN
PCFILASALDOCNB              EQUIPAMENTO VARCHAR2(100)                                            Equipamento inclusão            OPERACIONAL                        NaN
PCFILASALDOCNB                   ROTINA VARCHAR2(100)                                                 Rotina inclusão            OPERACIONAL                        NaN
PCFILASALDOCNB                  USUARIO VARCHAR2(100)                                                Usuario inclusão            OPERACIONAL                        NaN
PCFILASALDOCNB                 DATAHORA          DATE                                              Data hora inclusão            OPERACIONAL                        NaN
PCFILASALDOCNB              CODPARCEIRO  NUMBER(10,0)                                             Código do parceiro             OPERACIONAL                        NaN
PCFILASALDOCNB             TIPOPARCEIRO   VARCHAR2(1) Define o tipo do parceiro, se é: fornecedor, RCA, cliente e etc            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*