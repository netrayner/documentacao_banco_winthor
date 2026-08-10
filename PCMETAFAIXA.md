# 📊 Tabela: PCMETAFAIXA

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAFAIXA        CODIGO  NUMBER(8,0)                                      Indica o código da meta relacionada.            OPERACIONAL                        NaN
PCMETAFAIXA     CODFILIAL  VARCHAR2(2)                                                Indica o código da filial.            OPERACIONAL                        NaN
PCMETAFAIXA      TIPOMETA  VARCHAR2(2)                                                    Indica o tipo de meta.            OPERACIONAL                        NaN
PCMETAFAIXA      DTINICIO         DATE              Indica a data de início do período de vigência da pontuação.            OPERACIONAL                        NaN
PCMETAFAIXA         DTFIM         DATE               Indica a data de final do período de vigência da pontuação.            OPERACIONAL                        NaN
PCMETAFAIXA        COLUNA VARCHAR2(32)           Indica o nome da coluna de meta a que se refere esta pontuação.            OPERACIONAL                        NaN
PCMETAFAIXA      FAIXAINI NUMBER(12,4)                    Indica o % de início desta faixa de pontuação da meta.            OPERACIONAL                        NaN
PCMETAFAIXA      FAIXAFIM NUMBER(12,4)                     Indica o % de final desta faixa de pontuação da meta.            OPERACIONAL                        NaN
PCMETAFAIXA      QTPONTOS  NUMBER(8,2) Indica a quantidade de pontos ao atingir a meta nesta faixa de pontuação.            OPERACIONAL                        NaN
PCMETAFAIXA    TIPOPREMIO  VARCHAR2(2)                                               Indica o tipo de premiação.            OPERACIONAL                        NaN
PCMETAFAIXA       CODIGO2  NUMBER(8,0)                              Indica o segundo código da meta relacionada.            OPERACIONAL                        NaN
PCMETAFAIXA      CODMETAC  NUMBER(8,0)                                 Indica o valor da chave da tabela PCMETAC            OPERACIONAL                        NaN
PCMETAFAIXA       CODUSUR  NUMBER(4,0)                                                    Indica o codigo do RCA            OPERACIONAL                        NaN
PCMETAFAIXA CODSUPERVISOR  NUMBER(4,0)                                             Indica o codigo do Supervisor            OPERACIONAL                        NaN
PCMETAFAIXA    DTMXSALTER         DATE                                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*