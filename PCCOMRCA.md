# 📊 Tabela: PCCOMRCA

### Estrutura de Colunas e Restrições

  Tabela                   Coluna Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMRCA                CODFILIAL  VARCHAR2(2)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA               DATAINICIO         DATE                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA                  DATAFIM         DATE                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA            CODSUPERVISOR  NUMBER(4,0)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA                  CODUSUR  NUMBER(4,0)                                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA                     QTNF  NUMBER(6,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                  VLVENDA NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                   PERCOM  NUMBER(7,4)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA               VLCOMISSAO NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA              VLDEVOLUCAO NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA           VLESTORNODEVOL NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                   VLVALE NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                  VLVALOR NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                PERPAGCOM  NUMBER(5,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                  DTFECHA         DATE                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                     TIPO  VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                 NUMTRANS  NUMBER(8,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                PERCOMPAG  NUMBER(5,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA             CODFUNCFECHA  NUMBER(8,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA               CODFUNCALT  NUMBER(8,0)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA               PERCOMORIG  NUMBER(5,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA              VLCOMISORIG NUMBER(12,2)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA                CODROTINA  NUMBER(6,0)                                                           Indica o código da rotina que a comissão foi gerada.            OPERACIONAL                        NaN
PCCOMRCA              TIPOPERIODO VARCHAR2(20)                                         Indica o tipo de período informado na 1266: Faturamento ou Fechamento.            OPERACIONAL                        NaN
PCCOMRCA         TIPOPREPCOMISSAO  VARCHAR2(1)                                                                Tipo de comissao L - liquidez   F - faturamento            OPERACIONAL                        NaN
PCCOMRCA                VALORINSS NUMBER(12,2)                                                                        Valor do imposto INSS sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA                VALORIRRF NUMBER(12,2)                                                                    Valor do imposto de renda sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA         VALORTOTIMPOSTOS NUMBER(12,2)                                                         Soma dos impostos para o cálculo de comissão de venda.            OPERACIONAL                        NaN
PCCOMRCA                 VALORISS NUMBER(12,2)                                                                         Valor do imposto ISS sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA                VALORCSRF NUMBER(12,2)                                                                                Valor do CSRF sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA                 VALORPIS NUMBER(12,2)                                                                                 Valor do PIS sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA              VALORCOFINS NUMBER(12,2)                                                                              Valor do COFINS sobre a comissão.            OPERACIONAL                        NaN
PCCOMRCA      VLVALECONSIDERADOBC NUMBER(12,2)                                                     Valor de vales considerados na base de cálculo do imposto.            OPERACIONAL                        NaN
PCCOMRCA        TIPOVALORCOMISSAO  VARCHAR2(3)                  Este campo corresponde ao tipo de valor recebido ultilizado no cálculo para gerar a comissão.            OPERACIONAL                        NaN
PCCOMRCA          RECNUM_PCCORREN  NUMBER(8,0)                              Campo corresponde ao número do vale lançado ao realizar o fechamento da comissão.            OPERACIONAL                        NaN
PCCOMRCA            RECNUM_PCLANC  NUMBER(8,0)                    Campo corresponde ao número do contas a pagar lançado ao realizar o fechamento da comissão.            OPERACIONAL                        NaN
PCCOMRCA   RECNUM_PCCORREN_ADIANT  NUMBER(8,0)                                                              Este campo corresponde ao número do vale lançado.            OPERACIONAL                        NaN
PCCOMRCA        COMISSAOEXPORTADA  VARCHAR2(1)                                                                                            Comissão exportada.            OPERACIONAL                        NaN
PCCOMRCA             CONTROLADORM  VARCHAR2(1)                                                                                            Controlado pelo RM.            OPERACIONAL                        NaN
PCCOMRCA        CODCONTAGERENCIAL NUMBER(10,0)                                                                                     Código da conta gerencial.            OPERACIONAL                        NaN
PCCOMRCA       DTCOMPETENCIAFOLHA         DATE                                                                                        Data competência folha.            OPERACIONAL                        NaN
PCCOMRCA      PERCCOMISSAORATEADA  NUMBER(5,2)                                          Campo corresponde ao percentual da comissão rateada por RCA/Operador.            OPERACIONAL                        NaN
PCCOMRCA      TIPOCOMISSAORATEADA  NUMBER(1,0) Campo corresponde a qual percentual de rateio foi considerado, o informado na tela ou o cadastrado para o RCA.            OPERACIONAL                        NaN
PCCOMRCA  TIPOFUNCCOMISSAORATEADA  VARCHAR2(2)                           Campo corresponde a qual tipo de funcionario a comissão corresponde RCA ou Operador.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMRCA CRITERIOCOMISSAOLIQUIDEZ VARCHAR2(10)                                                                  Critério de apuração da comissão por liquidez            OPERACIONAL                        NaN
PCCOMRCA         COMISSAOAGRUPADA  VARCHAR2(1)                                                                    Identifica se é para usar comissão agrupada            OPERACIONAL                        NaN
PCCOMRCA      CODCOMISSAOAGRUPADA  NUMBER(8,0)                                                                                        Id da comissão agrupada            OPERACIONAL                        NaN
PCCOMRCA               VLFATORCOM NUMBER(12,2)                                                                                     Valor do fator de comissão            OPERACIONAL                        NaN
PCCOMRCA             CODIGOCOMRCA NUMBER(14,0)                                                          Campo para identificar os vales que compõe a comissão            OPERACIONAL                        NaN
PCCOMRCA             TIPOCOMISSAO  VARCHAR2(1)                                                                         Tipo de comissão (Produto, RCA, Outro)            OPERACIONAL                        NaN
PCCOMRCA                   NUMSEQ NUMBER(18,0)                                                                                              Número Sequencial            OPERACIONAL                        NaN
PCCOMRCA                  DIASDSR  NUMBER(3,0)                                                                            Dias de descanso semanal remunerado            OPERACIONAL                        NaN
PCCOMRCA                 VALORDSR NUMBER(12,2)                                                                           Valor do descanso semanal remunerado            OPERACIONAL                        NaN
PCCOMRCA          DATAINICIOVALES         DATE                                                                                       DATA DO PERIODO DE VALES            OPERACIONAL                        NaN
PCCOMRCA             DATAFIMVALES         DATE                                                                                   DATA FIM DO PERIODO DE VALES            OPERACIONAL                        NaN
PCCOMRCA            DEDUZVLOUTRAS  VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA               DEDUZFRETE  VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCCOMRCA            ABATERVALERCA  VARCHAR2(1)                                              Campo para definir se irá incluir os vales para fechamento do Rca            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*