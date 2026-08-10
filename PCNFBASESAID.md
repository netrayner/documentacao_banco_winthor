# 📊 Tabela: PCNFBASESAID

### Estrutura de Colunas e Restrições

      Tabela              Coluna  Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFBASESAID         CODFILIALNF   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID       NUMTRANSVENDA  NUMBER(10,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             ESPECIE   VARCHAR2(3)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID               SERIE   VARCHAR2(3)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             NUMNOTA  NUMBER(10,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             DTSAIDA          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID            DTCANCEL          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              CODCLI   NUMBER(6,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             PERCICM  NUMBER(10,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID                  UF   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             VLTOTAL  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             CODCONT  VARCHAR2(10)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           CODFISCAL   NUMBER(8,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              VLBASE  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              VLICMS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           VLISENTAS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID            VLOUTRAS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID                 OBS VARCHAR2(150)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID                FLAG   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID        VLDESDOBRADO  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           TIPOVENDA   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              BASEST  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID                VLST  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           VLBASEIPI  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID               VLIPI  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID             PERCIPI  NUMBER(10,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              DTGERA          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID       BCIMPESTADUAL  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID       VLIMPESTADUAL  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID              TIPOFJ   VARCHAR2(1)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID         VLPISRETIDO  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           VLREPASSE  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASESAID           VLBASEBCR  NUMBER(18,2)                                                                       Valor Base de cálculo BCR.             OPERACIONAL                        NaN
PCNFBASESAID             VLSTBCR  NUMBER(18,2)                                                                                    Valor de BCR.             OPERACIONAL                        NaN
PCNFBASESAID        TIPOREGISTRO   VARCHAR2(2) Identifica o tipo do registro do livro fiscal (N - normal, D - Despesas Acessórias e F - Frete).             OPERACIONAL                        NaN
PCNFBASESAID      VLISENTAS_DAPI  NUMBER(12,2)                                               Valor de isentas para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID      VLNAOTRIB_DAPI  NUMBER(12,2)                                        Valor de não tributados para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID      VLBASERED_DAPI  NUMBER(12,2)                            Valor de redução de base de cálculo para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID    VLSUSPENSAS_DAPI  NUMBER(12,2)                                             Valor de suspensas para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID           VLST_DAPI  NUMBER(12,2)                               Valor de substituição tributária para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID       VLOUTRAS_DAPI  NUMBER(12,2)                                                Valor de outras para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASESAID             CLIENTE  VARCHAR2(60)                                                                 Indica a razão social do cliente.            OPERACIONAL                        NaN
PCNFBASESAID                 CGC  VARCHAR2(18)                                                                         Indica o CNPJ do cliente.            OPERACIONAL                        NaN
PCNFBASESAID                  IE  VARCHAR2(15)                                                                Indica a insc. estadual do cliente            OPERACIONAL                        NaN
PCNFBASESAID        VLISENTASIPI  NUMBER(12,2)                                                                 Indica o valor de isenção do IPI.            OPERACIONAL                        NaN
PCNFBASESAID         VLOUTRASIPI  NUMBER(12,2)                                                                  indica o valor de outras do IPI.            OPERACIONAL                        NaN
PCNFBASESAID         VLBASEFRETE  NUMBER(12,2)                                                      Indica o valor base do frete na nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID    VLBASEOUTRASDESP  NUMBER(12,2)                                           Indica o valor base despesas acessorias na nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID             VLFRETE  NUMBER(12,2)                                                           Indica o valor do frete na nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID        VLOUTRASDESP  NUMBER(12,2)                                                Indica o valor despesas acessorias na nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID            SUBSERIE   VARCHAR2(2)                                                                 Indica a subsérie da nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID       VLBASENAOTRIB  NUMBER(12,2)                                                                Indica o valor base não tributado.            OPERACIONAL                        NaN
PCNFBASESAID             CODOPER   VARCHAR2(2)                                                                      Indica o código da operação.            OPERACIONAL                        NaN
PCNFBASESAID            UFFILIAL   VARCHAR2(2)                                                                            Indica a UF da filial.            OPERACIONAL                        NaN
PCNFBASESAID               VLPIS  NUMBER(16,2)                                                                            Indica o valor do PIS.            OPERACIONAL                        NaN
PCNFBASESAID            VLCOFINS  NUMBER(16,2)                                                                         Indica o valor do COFINS.            OPERACIONAL                        NaN
PCNFBASESAID      VLBASE_REDUCAO  NUMBER(12,2)                                                        Indica o valor da redução de base de ICMS.            OPERACIONAL                        NaN
PCNFBASESAID        BASESTFORANF  NUMBER(16,2)                                                          Indica a base do ST fora da nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID          VLSTFORANF  NUMBER(16,2)                                                         Indica o valor de ST fora da nota fiscal.            OPERACIONAL                        NaN
PCNFBASESAID     VLBASEOUTRASIPI  NUMBER(16,2)                                             Indica o valor base não tributada do IPI para outras.            OPERACIONAL                        NaN
PCNFBASESAID    VLBASEISENTASIPI  NUMBER(16,2)                                            Indica o valor base não tributada do IPI para isentas.            OPERACIONAL                        NaN
PCNFBASESAID      VLICMSDIFERIDO  NUMBER(12,2)                                                                            Valor do ICMS Diferido            OPERACIONAL                        NaN
PCNFBASESAID           SITTRIBUT   VARCHAR2(3)                                                                   Situação Tributária do registro            OPERACIONAL                        NaN
PCNFBASESAID      PERCICMNAOTRIB  NUMBER(10,2)                                                                  Percentual do ICMS não tributado            OPERACIONAL                        NaN
PCNFBASESAID       VLICMSNAOTRIB  NUMBER(12,2)                                                                       Valor do ICMS não tributado            OPERACIONAL                        NaN
PCNFBASESAID    VLDESCREDUCAOPIS  NUMBER(24,6)                                                               Valor de Desconto da Redução do PIS            OPERACIONAL                        NaN
PCNFBASESAID VLDESCREDUCAOCOFINS  NUMBER(24,6)                                                            Valor de Desconto da Redução do COFINS            OPERACIONAL                        NaN
PCNFBASESAID     VLCREDPRESUMIDO  NUMBER(20,2)                                                                       Valor do crédito presumido.            OPERACIONAL                        NaN
PCNFBASESAID               VLFCP  NUMBER(22,2)                                     Valor do fundo de combate a pobreza destinado a UF de Destino            OPERACIONAL                        NaN
PCNFBASESAID         VLICMSUFREM  NUMBER(22,2)                                                Valor do ICMS interestadual para a UF do Remetente            OPERACIONAL                        NaN
PCNFBASESAID        VLICMSUFDEST  NUMBER(22,2)                                                  Valor do ICMS Interestadual para a UF de Destino            OPERACIONAL                        NaN
PCNFBASESAID   VLICMSDIFALIQPART  NUMBER(22,2)                                                                                    valor do difal            OPERACIONAL                        NaN
PCNFBASESAID      VLBASEPARTDEST  NUMBER(22,2)                                                     valor da base da partilha para o destinatario            OPERACIONAL                        NaN
PCNFBASESAID      VLIPIDEVFORNEC        NUMBER                                                                    Valor IPI Devolução fornecedor            OPERACIONAL                        NaN
PCNFBASESAID              VLFECP  NUMBER(18,6)                                                                                        Valor FECP            OPERACIONAL                        NaN
PCNFBASESAID   VLACRESCIMOFUNCEP  NUMBER(18,6)                                   Valor de Acréscimo do Fundo de Combate e Erradicação da Pobreza            OPERACIONAL                        NaN
PCNFBASESAID  PERACRESCIMOFUNCEP   NUMBER(8,4)                                                                    Percentual de acrescimento FCP            OPERACIONAL                        NaN
PCNFBASESAID       VLBASEFCPICMS  NUMBER(18,6)                                                                       Base de Cálculo do FCP ICMS            OPERACIONAL                        NaN
PCNFBASESAID         VLBASEFCPST  NUMBER(18,6)                                                                         Base de Cálculo do FCP ST            OPERACIONAL                        NaN
PCNFBASESAID        ALIQICMSFECP   NUMBER(8,4)                                                                                Alíquota do FCP ST            OPERACIONAL                        NaN
PCNFBASESAID           VLICMSBCR  NUMBER(18,6)                                                            Valor ICMS de Base Cálculo de Retenção            OPERACIONAL                        NaN
PCNFBASESAID            VLICMSBR  NUMBER(18,6)                                                            Valor ICMS de Base Cálculo de Retenção            OPERACIONAL                        NaN
PCNFBASESAID          VLDESCONTO  NUMBER(12,2)                                             Valor do Desconto conforme regra de cada tipo de nota            OPERACIONAL                        NaN
PCNFBASESAID           VLPRODUTO  NUMBER(12,2)                                            Valor dos produtos conforme cada regra de tipo de nota            OPERACIONAL                        NaN
PCNFBASESAID              NUMSQL   VARCHAR2(2)                                                                                     NUMERO DO SQL            OPERACIONAL                        NaN
PCNFBASESAID         VBASEIBSCBS  NUMBER(15,2)                                                               Valor da base de cálculo do IBS/CBS            OPERACIONAL                        NaN
PCNFBASESAID               VLCBS  NUMBER(15,2)                                                                                      Valor do CBS            OPERACIONAL                        NaN
PCNFBASESAID            VLIBSMUN  NUMBER(15,2)                                                                            Valor do IBS Municipal            OPERACIONAL                        NaN
PCNFBASESAID             VLIBSUF  NUMBER(15,2)                                                                             Valor do IBS Estadual            OPERACIONAL                        NaN
PCNFBASESAID             VBASEIS  NUMBER(15,2)                                                                             Base de cálculo do IS            OPERACIONAL                        NaN
PCNFBASESAID                VLIS  NUMBER(15,2)                                                                                       Valor do IS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*