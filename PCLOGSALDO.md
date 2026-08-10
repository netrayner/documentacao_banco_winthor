# 📊 Tabela: PCLOGSALDO

### Estrutura de Colunas e Restrições

    Tabela                        Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGSALDO                      CODSALDO  NUMBER(20,0)                                     Chave tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGSALDO                     CODFILIAL   VARCHAR2(2)                                    Código filial            OPERACIONAL                        NaN
PCLOGSALDO                 CODPLANOCONTA   NUMBER(5,0)                               Código plano conta            OPERACIONAL                        NaN
PCLOGSALDO                           MES   NUMBER(2,0)                                              Mês            OPERACIONAL                        NaN
PCLOGSALDO                           ANO   NUMBER(4,0)                                              Ano            OPERACIONAL                        NaN
PCLOGSALDO                CODREDUZIDO_PC  VARCHAR2(12)                         Código reduzido da conta            OPERACIONAL                        NaN
PCLOGSALDO                   VALORDEBITO  NUMBER(22,2)                                     Valor debito            OPERACIONAL                        NaN
PCLOGSALDO                  VALORCREDITO  NUMBER(22,2)                                    Valor crédito            OPERACIONAL                        NaN
PCLOGSALDO            VLRDEBENCERRAMENTO  NUMBER(22,2)                        Valor debito encerramento            OPERACIONAL                        NaN
PCLOGSALDO            VLRCREENCERRAMENTO  NUMBER(22,2)                       Valor crédito encerramento            OPERACIONAL                        NaN
PCLOGSALDO                LOTEIMPORTACAO  NUMBER(10,0)                                  Lote importação            OPERACIONAL                        NaN
PCLOGSALDO                  VLRDEBCONCIL  NUMBER(22,2)                         Valor debito conciliação            OPERACIONAL                        NaN
PCLOGSALDO                  VLRCRECONCIL  NUMBER(22,2)                        Valor credito conciliação            OPERACIONAL                        NaN
PCLOGSALDO      VLRDEBCONCILENCERRAMENTO  NUMBER(22,2)            Valor debito conciliação encerramento            OPERACIONAL                        NaN
PCLOGSALDO      VLRCRECONCILENCERRAMENTO  NUMBER(22,2)           Valor credito conciliação encerramento            OPERACIONAL                        NaN
PCLOGSALDO              CODCONFEXERCICIO   NUMBER(8,0)                    Código configuração exercício            OPERACIONAL                        NaN
PCLOGSALDO                      PROGRAMA VARCHAR2(100)                               Programa alteração            OPERACIONAL                        NaN
PCLOGSALDO                   EQUIPAMENTO VARCHAR2(100)                            Equipamento alteração            OPERACIONAL                        NaN
PCLOGSALDO                       USUARIO VARCHAR2(100)                                Usuario alteração            OPERACIONAL                        NaN
PCLOGSALDO                       DATALOG          DATE                                   Data alteração            OPERACIONAL                        NaN
PCLOGSALDO                 TIPO_OPERACAO   VARCHAR2(5)                                    Tipo operação            OPERACIONAL                        NaN
PCLOGSALDO                USUARIOWINTHOR VARCHAR2(100)                        Usuario alteração Winthor            OPERACIONAL                        NaN
PCLOGSALDO                CODFILIAL_NOVO   VARCHAR2(2)                            Novo código de filial            OPERACIONAL                        NaN
PCLOGSALDO            CODPLANOCONTA_NOVO   NUMBER(5,0)                              Novo plano de conta            OPERACIONAL                        NaN
PCLOGSALDO                      MES_NOVO   NUMBER(2,0)                                         Novo mês            OPERACIONAL                        NaN
PCLOGSALDO                      ANO_NOVO   NUMBER(4,0)                                         Novo ano            OPERACIONAL                        NaN
PCLOGSALDO           CODREDUZIDO_PC_NOVO  VARCHAR2(12)                             Novo código reduzido            OPERACIONAL                        NaN
PCLOGSALDO              VALORDEBITO_NOVO  NUMBER(22,2)                             Novo valor de débito            OPERACIONAL                        NaN
PCLOGSALDO             VALORCREDITO_NOVO  NUMBER(22,2)                            Novo valor de credito            OPERACIONAL                        NaN
PCLOGSALDO       VLRDEBENCERRAMENTO_NOVO  NUMBER(22,2)             Novo valor de débito do encerramento            OPERACIONAL                        NaN
PCLOGSALDO       VLRCREENCERRAMENTO_NOVO  NUMBER(22,2)            Novo valor de credito do encerramento            OPERACIONAL                        NaN
PCLOGSALDO           LOTEIMPORTACAO_NOVO  NUMBER(10,0)                          Novo lote de importação            OPERACIONAL                        NaN
PCLOGSALDO             VLRDEBCONCIL_NOVO  NUMBER(22,2)                  Novo valor de débito conciliado            OPERACIONAL                        NaN
PCLOGSALDO             VLRCRECONCIL_NOVO  NUMBER(22,2)                 Novo valor de credito conciliado            OPERACIONAL                        NaN
PCLOGSALDO VLRDEBCONCILENCERRAMENTO_NOVO  NUMBER(22,2) Novo valor de débito conciliado do encerramento.            OPERACIONAL                        NaN
PCLOGSALDO VLRCRECONCILENCERRAMENTO_NOVO  NUMBER(22,2) Novo valor de crédito conciliado do encerramento            OPERACIONAL                        NaN
PCLOGSALDO         CODCONFEXERCICIO_NOVO   NUMBER(8,0)          Novo código de conferência do exercício            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*