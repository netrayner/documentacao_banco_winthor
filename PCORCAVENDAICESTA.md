# 📊 Tabela: PCORCAVENDAICESTA

### Estrutura de Colunas e Restrições

           Tabela                 Coluna  Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAICESTA                NUMORCA  NUMBER(10,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAICESTA                 NUMPED  NUMBER(10,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                CODPROD   NUMBER(6,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAICESTA                 NUMSEQ  NUMBER(20,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAICESTA            CODAUXILIAR  NUMBER(16,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA              CODPRODMP   NUMBER(6,0)                                                                                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCORCAVENDAICESTA                   QTMP  NUMBER(20,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 PVENDA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PTABELA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA               PBASERCA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA               BASEICST  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                     ST  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA          STCLIENTEGNRE  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PERCIPI  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  VLIPI  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PERCISS   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  VLISS  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA          VLDESCSUFRAMA  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA             VLCUSTOFIN  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA            VLCUSTOREAL  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA             VLCUSTOREP  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA            VLCUSTOCONT  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA         VLDESCCUSTOCMV  NUMBER(12,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  CODST   NUMBER(4,0)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 PERCOM   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA             PERDESCTAB   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                    IVA   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA              ALIQICMS1   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA              ALIQICMS2   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  PAUTA   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA            PERCBASERED   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA            CUSTOFINEST  NUMBER(18,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA     PERCBASEREDSTFONTE   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA          PERCBASEREDST   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA           PERDESCCUSTO   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA              CODICMTAB   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA                TXVENDA   NUMBER(8,6)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA            PERFRETECMV   NUMBER(8,4)                                                                                               NaN            OPERACIONAL                        NaN
PCORCAVENDAICESTA         VLDIFALIQUOTAS  NUMBER(18,6)                                                                  Valor da diferença de aliquotas.            OPERACIONAL                        NaN
PCORCAVENDAICESTA       BASEDIFALIQUOTAS  NUMBER(18,6)                                                                Base da diferença entre alíquotas.            OPERACIONAL                        NaN
PCORCAVENDAICESTA       PERCDIFALIQUOTAS   NUMBER(8,4)                                                            Percentual de diferença de tributação.            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PERCOM2   NUMBER(8,4)                                                       Indica a comissão do primeiro profissional.            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PERCOM3   NUMBER(8,4)                                                        Indica a comissão do segundo profissional.            OPERACIONAL                        NaN
PCORCAVENDAICESTA                PERCOM4   NUMBER(8,4)                                                       Indica a comissão do terceiro profissional.            OPERACIONAL                        NaN
PCORCAVENDAICESTA         VLBASEPARTDEST  NUMBER(18,6)                                                         Valor da base de calculo na Uf de destino            OPERACIONAL                        NaN
PCORCAVENDAICESTA                ALIQFCP  NUMBER(18,6)                                                      Aliquota de FCP (fundo de combate a pobreza)            OPERACIONAL                        NaN
PCORCAVENDAICESTA        ALIQINTERNADEST  NUMBER(18,6)                                                         Aliquota de ICMS interna na UF de destino            OPERACIONAL                        NaN
PCORCAVENDAICESTA              VLFCPPART  NUMBER(18,6)                                                                                   Valor do FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAICESTA         VLICMSPARTDEST  NUMBER(18,6)                                                     Valor do ICMS Interestadual para a UF Destino            OPERACIONAL                        NaN
PCORCAVENDAICESTA             VLICMSPART  NUMBER(18,6)       Valor de ICMS de partilha (valor que deverá ser utilizado para acrescer o valor do produto)            OPERACIONAL                        NaN
PCORCAVENDAICESTA        PERCBASEREDPART   NUMBER(5,2)                                                 Redução aplicada na base de Partilha no orçamento            OPERACIONAL                        NaN
PCORCAVENDAICESTA           PERCPROVPART   NUMBER(5,2)                                                         Percentual provisório de partilha de ICMS            OPERACIONAL                        NaN
PCORCAVENDAICESTA      VLICMSDIFALIQPART  NUMBER(22,6)                                      Valor de ICMS do diferencial de aliquota da partilha de ICMS            OPERACIONAL                        NaN
PCORCAVENDAICESTA          VLICMSPARTREM  NUMBER(18,6)                                                       Valor do ICMS de partilha para UF remetente            OPERACIONAL                        NaN
PCORCAVENDAICESTA      ALIQINTERORIGPART  NUMBER(18,6)                                                                     Valor de ICMS da UF de origem            OPERACIONAL                        NaN
PCORCAVENDAICESTA           VLIPIPTABELA  NUMBER(18,6)                                                          Valor de IPI relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAICESTA          VLIPIPBASERCA  NUMBER(18,6)                                                           Valor de IPI relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAICESTA              STPTABELA  NUMBER(18,6)                                                           Valor de ST relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAICESTA             STPBASERCA  NUMBER(18,6)                                                            Valor de ST relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAICESTA      VLICMSPARTPTABELA  NUMBER(18,6)                                                   Valor ICMS Partilha relativo ao preço de tabela            OPERACIONAL                        NaN
PCORCAVENDAICESTA     VLICMSPARTPBASERCA  NUMBER(18,6)                                                    Valor ICMS Partilha relativo ao preço base RCA            OPERACIONAL                        NaN
PCORCAVENDAICESTA              CODFISCAL   NUMBER(8,0)                                                        Define o CFOP do item no orçamento (Cesta)            OPERACIONAL                        NaN
PCORCAVENDAICESTA              SITTRIBUT   VARCHAR2(3)                                                         Define o CST do item no orçamento (Cesta)            OPERACIONAL                        NaN
PCORCAVENDAICESTA           CODPRODTINTA  VARCHAR2(40)                                                                           CÓDIGO DO PRODUTO TINTA            OPERACIONAL                        NaN
PCORCAVENDAICESTA          VLBASEFCPICMS  NUMBER(18,6)                                            Valor da base de calculo do Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCORCAVENDAICESTA            VLBASEFCPST  NUMBER(18,6)                                         Valor de base de calculo do Fundo de Combate a Pobreza ST            OPERACIONAL                        NaN
PCORCAVENDAICESTA           VLBCFCPSTRET  NUMBER(18,6)                                       Valor da base de calculo do FCP retido anteriormente por ST            OPERACIONAL                        NaN
PCORCAVENDAICESTA            PERFCPSTRET  NUMBER(12,4)                                Percentual do FCP retido anteriormente por Substituição Tributaria            OPERACIONAL                        NaN
PCORCAVENDAICESTA             VLFCPSTRET  NUMBER(18,6)                                                   Valor do FCP retido por Substituição Tributária            OPERACIONAL                        NaN
PCORCAVENDAICESTA               PERFCPSN  NUMBER(12,4)                                        Aliquota aplicável de cálculo do crédito(SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCORCAVENDAICESTA        VLCREDFCPICMSSN  NUMBER(18,6) Valor crédito do ICMS que pode ser aproveitado nos termos do art. 23 da LC 123 (SIMPLES NACIONAL)            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 VLFECP  NUMBER(18,6)                                                                                       Valor Fecp.            OPERACIONAL                        NaN
PCORCAVENDAICESTA      VLACRESCIMOFUNCEP  NUMBER(18,6)                                                                            Valor Acrescimo FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAICESTA     PERACRESCIMOFUNCEP  NUMBER(12,4)                                                                       Percentual Acrescimo FUNCEP            OPERACIONAL                        NaN
PCORCAVENDAICESTA           ALIQICMSFECP  NUMBER(12,4)                                                                            Alíquota de ICMS Fecp.            OPERACIONAL                        NaN
PCORCAVENDAICESTA   UTILIZOUMOTORCALCULO   VARCHAR2(1)                                Indica se utilizou motor de calculo para calcular o preço de venda            OPERACIONAL                        NaN
PCORCAVENDAICESTA                ALIQCBS NUMBER(23,10)                                                                Aliquota para calculo do valor CBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                ALIQIBS NUMBER(23,10)                                                                Aliquota para calculo do valor IBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 ALIQIS NUMBER(23,10)                                                                 Aliquota para calculo do valor IS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                BASECBS NUMBER(23,10)                                                              Valor base para calculo do valor CBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                BASEIBS NUMBER(23,10)                                                              Valor base para calculo do valor IBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 BASEIS NUMBER(23,10)                                                               Valor base para calculo do valor IS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  VLCBS NUMBER(23,10)                                                                              Valor do imposto CBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  VLIBS NUMBER(23,10)                                                                              Valor do imposto IBS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                   VLIS NUMBER(23,10)                                                                               Valor do imposto IS            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 CODCBS  NUMBER(10,0)                                        Código da tributação do imposto CBS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAICESTA                 CODIBS  NUMBER(10,0)                                        Código da tributação do imposto IBS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAICESTA                  CODIS  NUMBER(10,0)                                         Código da tributação do imposto IS na tabela PCTRIBUTACAO            OPERACIONAL                        NaN
PCORCAVENDAICESTA CPFRESPTECNICOAGRICOLA  VARCHAR2(11)                                                                  CPF Responsável Técnico Agrícola            OPERACIONAL                        NaN
PCORCAVENDAICESTA NUMRECEITUARIOAGRICOLA  VARCHAR2(30)                                                                       Número Receituário Agrícola            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*