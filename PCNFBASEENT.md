# 📊 Tabela: PCNFBASEENT

### Estrutura de Colunas e Restrições

     Tabela                    Coluna  Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFBASEENT               CODFILIALNF   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT               NUMTRANSENT  NUMBER(10,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 DTENTRADA          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 DTEMISSAO          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   ESPECIE   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                     SERIE   VARCHAR2(3)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   NUMNOTA  NUMBER(10,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 CODFORNEC   NUMBER(6,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                        UF   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   VLTOTAL  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   CODCONT  VARCHAR2(10)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 CODFISCAL   NUMBER(8,0)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                    VLBASE  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                    VLICMS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 VLISENTAS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                  VLOUTRAS  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                       OBS VARCHAR2(500)                                                                                        Observação            OPERACIONAL                        NaN
PCNFBASEENT                      FLAG   VARCHAR2(1)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   PERCICM  NUMBER(10,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT              VLDESDOBRADO  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT              TIPODESCARGA   VARCHAR2(1)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                    BASEST  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                      VLST  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                  ALIQUOTA   NUMBER(4,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                 VLBASEIPI  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                     VLIPI  NUMBER(12,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   PERCIPI  NUMBER(10,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                   ALIQDIF   NUMBER(4,2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                    DTGERA          DATE                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT                TIPOCOMPRA   VARCHAR2(2)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT             BCIMPESTADUAL  NUMBER(12,2)      Armazena o valor de ajuste da Base de Calc. do ICMS Retido especifico no caso de UF = PI/MA.            OPERACIONAL                        NaN
PCNFBASEENT             VLIMPESTADUAL  NUMBER(12,2)                       Armazena o valor de ajuste do ICMS Retido especifico no caso de UF = PI/MA.            OPERACIONAL                        NaN
PCNFBASEENT              BASESTFORANF  NUMBER(12,2)                                            Base de cálculo Substituição Tributária fora da nota.             OPERACIONAL                        NaN
PCNFBASEENT                VLSTFORANF  NUMBER(12,2)                                                   Valor da Substituição Tributária fora da nota.             OPERACIONAL                        NaN
PCNFBASEENT              TIPOREGISTRO   VARCHAR2(2) Identifica o tipo do registro do livro fiscal (N - normal, D - Despesas Acessórias e F - Frete).             OPERACIONAL                        NaN
PCNFBASEENT            VLISENTAS_DAPI  NUMBER(12,2)                                               Valor de isentas para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT            VLNAOTRIB_DAPI  NUMBER(12,2)                                        Valor de não tributados para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT            VLBASERED_DAPI  NUMBER(12,2)                            Valor de redução de base de cálculo para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT          VLSUSPENSAS_DAPI  NUMBER(12,2)                                             Valor de suspensas para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT                 VLST_DAPI  NUMBER(12,2)                               Valor de substituição tributária para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT             VLOUTRAS_DAPI  NUMBER(12,2)                                                Valor de outras para DAPI no campo de observação.             OPERACIONAL                        NaN
PCNFBASEENT                FORNECEDOR  VARCHAR2(60)                                                              Indica a razão social do fornecedor.            OPERACIONAL                        NaN
PCNFBASEENT                       CGC  VARCHAR2(18)                                                                         Indica o CNPJ do cliente.            OPERACIONAL                        NaN
PCNFBASEENT                        IE  VARCHAR2(15)                                                                Indica a insc. estadual do cliente            OPERACIONAL                        NaN
PCNFBASEENT              VLISENTASIPI  NUMBER(12,2)                                                                 Indica o valor de isenção do IPI.            OPERACIONAL                        NaN
PCNFBASEENT               VLOUTRASIPI  NUMBER(12,2)                                                                  indica o valor de outras do IPI.            OPERACIONAL                        NaN
PCNFBASEENT               VLBASEFRETE  NUMBER(12,2)                                                      Indica o valor Base do frete na nota fiscal.            OPERACIONAL                        NaN
PCNFBASEENT          VLBASEOUTRASDESP  NUMBER(12,2)                                           Indica o valor base despesas acessorias na nota fiscal.            OPERACIONAL                        NaN
PCNFBASEENT                   VLFRETE  NUMBER(12,2)                                                              Indica o valor frete na nota fiscal.            OPERACIONAL                        NaN
PCNFBASEENT              VLOUTRASDESP  NUMBER(12,2)                                                Indica o valor despesas acessorias na nota fiscal.            OPERACIONAL                        NaN
PCNFBASEENT             VLBASENAOTRIB  NUMBER(12,2)                                                                Indica o valor base não tributado.            OPERACIONAL                        NaN
PCNFBASEENT                   CODOPER   VARCHAR2(2)                                                                      Indica o código da operação.            OPERACIONAL                        NaN
PCNFBASEENT                  UFFILIAL   VARCHAR2(2)                                                                            Indica a UF da filial.            OPERACIONAL                        NaN
PCNFBASEENT                     VLPIS  NUMBER(16,2)                                                                            Indica o valor do PIS.            OPERACIONAL                        NaN
PCNFBASEENT                  VLCOFINS  NUMBER(16,2)                                                                         Indica o valor do COFINS.            OPERACIONAL                        NaN
PCNFBASEENT            VLBASE_REDUCAO  NUMBER(12,2)                                                        Indica o valor da redução de base de ICMS.            OPERACIONAL                        NaN
PCNFBASEENT           VLBASEOUTRASIPI  NUMBER(16,2)                                             Indica o valor base não tributada do IPI para outras.            OPERACIONAL                        NaN
PCNFBASEENT          VLBASEISENTASIPI  NUMBER(16,2)                                            Indica o valor base não tributada do IPI para isentas.            OPERACIONAL                        NaN
PCNFBASEENT                 SITTRIBUT   VARCHAR2(3)                                                                   Situação Tributária do registro            OPERACIONAL                        NaN
PCNFBASEENT            PERCICMNAOTRIB  NUMBER(10,2)                                                                  Percentual do ICMS não tributado            OPERACIONAL                        NaN
PCNFBASEENT             VLICMSNAOTRIB  NUMBER(12,2)                                                                       Valor do ICMS não tributado            OPERACIONAL                        NaN
PCNFBASEENT           VLCREDPRESUMIDO  NUMBER(20,2)                                                                       Valor do crédito presumido.            OPERACIONAL                        NaN
PCNFBASEENT                VLSISCOMEX  NUMBER(18,6)                                                           Valor referente a despesas com SISCOMEX            OPERACIONAL                        NaN
PCNFBASEENT              VLIMPORTACAO  NUMBER(18,6)                                                                    Valor do Imposto de Importação            OPERACIONAL                        NaN
PCNFBASEENT               VLCAPATAZIA  NUMBER(18,6)                                           Valor da capatazia rateado entre os itens de importação            OPERACIONAL                        NaN
PCNFBASEENT                   VLAFRMM  NUMBER(18,6)                                  Valor do Adicional de Frete para a Renovação da Marinha Mercante            OPERACIONAL                        NaN
PCNFBASEENT                  VLSEGURO  NUMBER(18,6)                                                                          Indica o valor do seguro            OPERACIONAL                        NaN
PCNFBASEENT               VLADUANEIRA  NUMBER(18,6)                                                                           Valor Despesa Aduaneira            OPERACIONAL                        NaN
PCNFBASEENT           VLOUTRASDESPIMP  NUMBER(18,6)                                                                  Valor Outras Despesas Importação            OPERACIONAL                        NaN
PCNFBASEENT             VLANTIDUMPING  NUMBER(18,6)                                                                                 Valor Antidumping            OPERACIONAL                        NaN
PCNFBASEENT               VLPISCALCDI  NUMBER(16,2)                                                 Valor Pis para cálculo do Documento de Importação            OPERACIONAL                        NaN
PCNFBASEENT            VLCOFINSCALCDI  NUMBER(16,2)                                              Valor Cofins para cálculo do Documento de Importação            OPERACIONAL                        NaN
PCNFBASEENT               VLFRETECONT  NUMBER(16,2)                                                                 Valor do Frete para contabilidade            OPERACIONAL                        NaN
PCNFBASEENT                     VLFCP  NUMBER(22,2)                                     Valor do fundo de combate a pobreza destinado a UF de Destino            OPERACIONAL                        NaN
PCNFBASEENT               VLICMSUFREM  NUMBER(22,2)                                                Valor do ICMS interestadual para a UF do Remetente            OPERACIONAL                        NaN
PCNFBASEENT              VLICMSUFDEST  NUMBER(22,2)                                                  Valor do ICMS Interestadual para a UF de Destino            OPERACIONAL                        NaN
PCNFBASEENT         VLICMSDIFALIQPART  NUMBER(22,2)                                                                                    valor do difal            OPERACIONAL                        NaN
PCNFBASEENT            VLBASEPARTDEST  NUMBER(22,2)                                                     valor da base da partilha para o destinatario            OPERACIONAL                        NaN
PCNFBASEENT             VLDIFALIQUOTA  NUMBER(16,2)                                                               Vl.total do diferêncial de alíquota            OPERACIONAL                        NaN
PCNFBASEENT            VLCREDITO_CIAP  NUMBER(16,2)                                                                          Vl.total do crédito CIAP            OPERACIONAL                        NaN
PCNFBASEENT      PERCIMPPRODUTORRURAL  NUMBER(16,2)                                                                              Vl.total do FUNRURAL            OPERACIONAL                        NaN
PCNFBASEENT       VLOUTROSCUSTOSCUSTO  NUMBER(22,2)                                                                            valor de outros custos            OPERACIONAL                        NaN
PCNFBASEENT          VLICMSANTECIPADO  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCNFBASEENT         VLIMPPRODUTORURAL  NUMBER(18,6)                                                                      Valor imposto Produtor Rural            OPERACIONAL                        NaN
PCNFBASEENT            VLOUTROSCUSTOS  NUMBER(18,6)                                                     Valor de outros custos do item de importação.            OPERACIONAL                        NaN
PCNFBASEENT                    VLFECP  NUMBER(18,6)                                                                                        Valor FECP            OPERACIONAL                        NaN
PCNFBASEENT         VLACRESCIMOFUNCEP  NUMBER(18,6)                                   Valor de Acréscimo do Fundo de Combate e Erradicação da Pobreza            OPERACIONAL                        NaN
PCNFBASEENT              VLDESPFORANF  NUMBER(18,6)                                                                 Valor Despesa fora da nota fiscal            OPERACIONAL                        NaN
PCNFBASEENT             VLFRETECONHEC  NUMBER(18,6)                                                                    Valor do Frete do Conhecimento            OPERACIONAL                        NaN
PCNFBASEENT        PERACRESCIMOFUNCEP   NUMBER(8,4)                                                                    Percentual de acrescimento FCP            OPERACIONAL                        NaN
PCNFBASEENT             VLBASEFCPICMS  NUMBER(18,6)                                                                       Base de Cálculo do FCP ICMS            OPERACIONAL                        NaN
PCNFBASEENT               VLBASEFCPST  NUMBER(18,6)                                                                         Base de Cálculo do FCP ST            OPERACIONAL                        NaN
PCNFBASEENT              ALIQICMSFECP   NUMBER(8,4)                                                                                Alíquota do FCP ST            OPERACIONAL                        NaN
PCNFBASEENT PERCREDBASEPISCOFINSFRETE  NUMBER(12,4)                                     Percentual de redução da base para o calculo pis/cofins Frete            OPERACIONAL                        NaN
PCNFBASEENT                 VLICMSBCR  NUMBER(18,6)                                                            Valor ICMS de Base Cálculo de Retenção            OPERACIONAL                        NaN
PCNFBASEENT                   VLSTBCR  NUMBER(18,6)                                                              Valor ST de Base Cálculo de Retenção            OPERACIONAL                        NaN
PCNFBASEENT                  VLICMSBR  NUMBER(18,6)                                                            Valor ICMS de Base Cálculo de Retenção            OPERACIONAL                        NaN
PCNFBASEENT              VLFECPSTGUIA  NUMBER(18,4)                                                                              Valor do fcp st Guia            OPERACIONAL                        NaN
PCNFBASEENT                 VLSUFRAMA  NUMBER(18,6)                                                                            Valor total do Suframa            OPERACIONAL                        NaN
PCNFBASEENT             VLBASESUFRAMA  NUMBER(18,6)                                                                            VLR DA BASE DO SUFRAMA            OPERACIONAL                        NaN
PCNFBASEENT                    NUMSQL   VARCHAR2(2)                                                                                     NUMERO DO SQL            OPERACIONAL                        NaN
PCNFBASEENT                 VLPRODUTO  NUMBER(18,6)                                                                                    VLR DO PRODUTO            OPERACIONAL                        NaN
PCNFBASEENT                VLDESCONTO  NUMBER(18,6)                                                                                 VALOR DO DESCONTO            OPERACIONAL                        NaN
PCNFBASEENT               VBASEIBSCBS  NUMBER(15,2)                                                               Valor da base de cálculo do IBS/CBS            OPERACIONAL                        NaN
PCNFBASEENT                     VLCBS  NUMBER(15,2)                                                                                      Valor do CBS            OPERACIONAL                        NaN
PCNFBASEENT                  VLIBSMUN  NUMBER(15,2)                                                                            Valor do IBS Municipal            OPERACIONAL                        NaN
PCNFBASEENT                   VLIBSUF  NUMBER(15,2)                                                                             Valor do IBS Estadual            OPERACIONAL                        NaN
PCNFBASEENT                   VBASEIS  NUMBER(15,2)                                                                             Base de cálculo do IS            OPERACIONAL                        NaN
PCNFBASEENT                      VLIS  NUMBER(15,2)                                                                                       Valor do IS            OPERACIONAL                        NaN
PCNFBASEENT                VLTOTALIBS  NUMBER(15,2)                                                                                Valor total de IBS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*