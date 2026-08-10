# 📊 Tabela: PCPEDIDOCIAP

### Estrutura de Colunas e Restrições

      Tabela                       Coluna  Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIDOCIAP                       NUMPED  NUMBER(10,0)                                                             Número do Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIDOCIAP                    DTEMISSAO          DATE                                                                 Data emissão            OPERACIONAL                        NaN
PCPEDIDOCIAP                    CODFORNEC   NUMBER(6,0)                                                         Código do Fornecedor            OPERACIONAL                        NaN
PCPEDIDOCIAP                    CODFILIAL   VARCHAR2(2)                                                             Código da filial            OPERACIONAL                        NaN
PCPEDIDOCIAP                      VLTOTAL  NUMBER(12,2)                                                        Valor total do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                   VLENTREGUE  NUMBER(12,2)                                                     Valor entregue do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                 TIPODESCARGA   VARCHAR2(1)                                                               Tipo do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                 CODCOMPRADOR   NUMBER(8,0)                                                          Código do Comprador            OPERACIONAL                        NaN
PCPEDIDOCIAP                   CODPARCELA   NUMBER(6,0)                                  Código parcelamento contas a pagar previsto            OPERACIONAL                        NaN
PCPEDIDOCIAP                    DTPREVENT          DATE                                                     Data previsão de entrega            OPERACIONAL                        NaN
PCPEDIDOCIAP                          OBS VARCHAR2(100)                                                                 Observação 1            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS2 VARCHAR2(100)                                                                 Observação 2            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS3 VARCHAR2(100)                                                                 Observação 3            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS4 VARCHAR2(100)                                                                 Observação 4            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS5 VARCHAR2(100)                                                                 Observação 5            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS6 VARCHAR2(100)                                                                 Observação 6            OPERACIONAL                        NaN
PCPEDIDOCIAP                         OBS7 VARCHAR2(100)                                                                 Observação 7            OPERACIONAL                        NaN
PCPEDIDOCIAP                 TIPOFRETEFOB   VARCHAR2(3)                                                                Tipo de frete            OPERACIONAL                        NaN
PCPEDIDOCIAP                CODFUNCLIBERA   NUMBER(8,0)                                           Código usuário liberação do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                     DTLIBERA          DATE                                                     Data liberação do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                CODROTINALANC   NUMBER(4,0)                                                    Rotina inclusão do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP              CODFUNCINCLUSAO   NUMBER(8,0)                                            Código usuário inclusão do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP             CODFUNCALTERACAO   NUMBER(8,0)                                           Código usuário alteração do pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP               CALCIPICOMDESC   VARCHAR2(1)                                          Calcular IPI com desconto comercial            OPERACIONAL                        NaN
PCPEDIDOCIAP            CALCIPICOMFRETENF   VARCHAR2(1)                                                   Calcular IPI com Frete CIF            OPERACIONAL                        NaN
PCPEDIDOCIAP    DEDUZIRSUFRAMACALCCREDICM   VARCHAR2(1)                      Deduzir SUFRAMA da base de calculo do Crédido Presumido            OPERACIONAL                        NaN
PCPEDIDOCIAP    DEDUZIRSUFRAMACALCCREDPIS   VARCHAR2(1)                            Deduzir SUFRAMA da base de calculo do PIS/COFINS.            OPERACIONAL                        NaN
PCPEDIDOCIAP    UTILIZAOUTRASDESPCALCICMS   VARCHAR2(1)                      Utiliza Outras Despesas/Seguro base de calculo do ICMS.            OPERACIONAL                        NaN
PCPEDIDOCIAP     CALCSUFRAMASOBREPLIQUIDO   VARCHAR2(1)                     Considera Desconto Comercial base de calculo do SUFRAMA.            OPERACIONAL                        NaN
PCPEDIDOCIAP      DEDUZIRSUFRAMABCSTALIQ1   VARCHAR2(1)                                  Considera SUFRAMA da base de calculo do ST.            OPERACIONAL                        NaN
PCPEDIDOCIAP       CALCULAPISCOFINSCOMIPI   VARCHAR2(1)                              Considera IPI da base de calculo do PIS/COFINS.            OPERACIONAL                        NaN
PCPEDIDOCIAP            CONSSTNFPISCOFINS   VARCHAR2(1)                            Considera ST NF da base de calculo do PIS/COFINS.            OPERACIONAL                        NaN
PCPEDIDOCIAP       USAPERCICMSNAALIQEXTST   VARCHAR2(1)            Utiliza alíquota de ICMS da NF do calculo do ST alíquota externa.            OPERACIONAL                        NaN
PCPEDIDOCIAP                     ISENTOST   VARCHAR2(1)                                                                 Isento de ST            OPERACIONAL                        NaN
PCPEDIDOCIAP           CALCULARIPIPESOLIQ   VARCHAR2(1)                            Calcular IPI por Quilo utilizando o pelo Líquido.            OPERACIONAL                        NaN
PCPEDIDOCIAP       CONSIPICALCBASECREPRES   VARCHAR2(1)                       Considera IPI da base de calculo do Crédito Presumido.            OPERACIONAL                        NaN
PCPEDIDOCIAP            CONSIPICALCBASEST   VARCHAR2(1)                                      Considera IPI da base de calculo do ST.            OPERACIONAL                        NaN
PCPEDIDOCIAP          UTILIZADESCCALCICMS   VARCHAR2(1)                          Utiliza Desconto Comercial base de cálculo do ICMS.            OPERACIONAL                        NaN
PCPEDIDOCIAP            UTILIZADESCCALCST   VARCHAR2(1)                            Utiliza Desconto Comercial base de cálculo do ST.            OPERACIONAL                        NaN
PCPEDIDOCIAP     UTILIZAOUTRASDESPCALCIPI   VARCHAR2(1)                       Utiliza Outras Despesas/Seguro base de calculo do IPI.            OPERACIONAL                        NaN
PCPEDIDOCIAP         UTILIZAFRETECALCICMS   VARCHAR2(1)                                 Utiliza Frete CIF na base de calculo do ICMS            OPERACIONAL                        NaN
PCPEDIDOCIAP    UTILIZAOUTDESPCALCSUFRAMA   VARCHAR2(1)                    Utiliza Outras Despesas/Seguro base de calculo do SUFRAMA            OPERACIONAL                        NaN
PCPEDIDOCIAP      DEDFRETECIFCREDPRESICMS   VARCHAR2(1)                       Utiliza Frete CIF na base de calculo do ICMS Presumido            OPERACIONAL                        NaN
PCPEDIDOCIAP         CONSMAIORICMSVLPAUTA   VARCHAR2(1) Considera maior valor entre o %IVA e Valor de Pauta p/ calculo da Base ICMS.            OPERACIONAL                        NaN
PCPEDIDOCIAP USAOUTRASDESPSEGUROPISCOFINS   VARCHAR2(1)                 Utiliza Outras Despesas/Seguro base de calculo do PIS/COFINS            OPERACIONAL                        NaN
PCPEDIDOCIAP           UTILIZAIPICALCICMS   VARCHAR2(1)                                       Utiliza IPI na base de calculo do ICMS            OPERACIONAL                        NaN
PCPEDIDOCIAP                  USADRAWBACK   VARCHAR2(1)                                                                 Usa Drawback            OPERACIONAL                        NaN
PCPEDIDOCIAP                     DTCANCEL          DATE                                               Data do Cancelamento do Pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                CODFUNCCANCEL   NUMBER(8,0)                                          Código do usuário cancelou o pedido            OPERACIONAL                        NaN
PCPEDIDOCIAP                NUMNEGOCIACAO  NUMBER(12,0)                                                         Número da negociação            OPERACIONAL                        NaN
PCPEDIDOCIAP               CODFORNECFRETE   NUMBER(6,0)                                              Código do fornecedor Transporte            OPERACIONAL                        NaN
PCPEDIDOCIAP                     CODCONTA  NUMBER(10,0)                                                              Código da conta            OPERACIONAL                        NaN
PCPEDIDOCIAP                DTCOMPETENCIA          DATE                                                          Data da competência            OPERACIONAL                        NaN
PCPEDIDOCIAP              TIPOFRETECIFFOB   VARCHAR2(1)                                   Modalidade de Frete que Transportou a Nota            OPERACIONAL                        NaN
PCPEDIDOCIAP          CALCDIFALIQUOTAICMS   VARCHAR2(4)                       Tipo de calculo de diferença de alíquota (Sistemática)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*