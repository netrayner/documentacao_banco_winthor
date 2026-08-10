# 📊 Tabela: PCMOVCR

### Estrutura de Colunas e Restrições

 Tabela                Coluna  Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVCR              NUMTRANS  NUMBER(10,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                  DATA          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR              CODBANCO   NUMBER(4,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                CODCOB   VARCHAR2(4)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                 VALOR  NUMBER(14,2)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                  TIPO   VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR             HISTORICO VARCHAR2(200)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR               NUMCARR  NUMBER(12,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR               VLSALDO  NUMBER(16,2)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                  HORA   NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                MINUTO   NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR               CODFUNC   NUMBER(8,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR              DTCONCIL          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           CONCILIACAO   VARCHAR2(2)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           CODCONTADEB  NUMBER(12,0)                                                                              Descricao coluna CODCONTADEB            OPERACIONAL                        NaN
PCMOVCR          CODCONTACRED  NUMBER(12,0)                                                                             Descricao coluna CODCONTACRED            OPERACIONAL                        NaN
PCMOVCR                INDICE   VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR             DTESTORNO          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           NUMTRANSEST  NUMBER(10,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR         VLSALDOCONCIL  NUMBER(14,2)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           DTVENCTICKT          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR            HISTORICO2 VARCHAR2(200)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR              SALDOTMP  NUMBER(14,2)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR              OPERACAO   NUMBER(2,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR             NUMCHEQUE  VARCHAR2(20)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR         CODROTINALANC   NUMBER(6,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR               ESTORNO   VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR         CODFUNCCONCIL   NUMBER(8,0)                                        Matrícula do funcionario que registrou a conciliacao do numerário.            OPERACIONAL                        NaN
PCMOVCR  CODFUNCESTORNOCONCIL   NUMBER(8,0)                                                      Matricula do funcionário que estornou a conciliação.            OPERACIONAL                        NaN
PCMOVCR               NUMLANC   NUMBER(8,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR             NUMCARREG   NUMBER(8,0)                     Número do Carregamento, conforme informado na [631 - Lançamento de Depesas/Receitas].            OPERACIONAL                        NaN
PCMOVCR   DTEXPORTACAOSERVINT          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR      EXPORTADOSERVINT   VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR    IMPORTADOSERVPRINC   VARCHAR2(1)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           NUMTRANSECF  NUMBER(10,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR DTIMPORTACAOSERVPRINC          DATE                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR            NUMVALEECF  NUMBER(10,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR                 NUMCX   NUMBER(4,0)                                                                                                       NaN            OPERACIONAL                        NaN
PCMOVCR           DUPLICBAIXA  NUMBER(10,0)                                                    Número da duplicata utilizada na baixa do lançamento.             OPERACIONAL                        NaN
PCMOVCR            PRESTBAIXA   VARCHAR2(2)                                       Número da prestação da duplicata utilizada na baixa do lançamento.             OPERACIONAL                        NaN
PCMOVCR         DTCOMPENSACAO          DATE                         Data de compensação do lançamento, informada pelo usuário. Gravado na rotina 604.            OPERACIONAL                        NaN
PCMOVCR             CODFILIAL   VARCHAR2(2)                                                                                Indica o código da filial.            OPERACIONAL                        NaN
PCMOVCR             CODCRECLI   NUMBER(6,0)                                                                              Indica o crédito de cliente.            OPERACIONAL                        NaN
PCMOVCR            VALORCAIXA  NUMBER(18,6)     Valor movimentação financeira títulos acertados rotina 403 onde a cobrança não seja baixa automática.            OPERACIONAL                        NaN
PCMOVCR                CODCLI   NUMBER(6,0)                                                                       Código do cliente associado ao DNI.            OPERACIONAL                        NaN
PCMOVCR         CODFUNCDNICLI   NUMBER(8,0)                                 Código do funcionário responsável por associar o cliente ao deposito DNI.            OPERACIONAL                        NaN
PCMOVCR       DTASSOCIADNICLI          DATE                                             Data em que foi realizada a associação entre o DNI e Cliente.            OPERACIONAL                        NaN
PCMOVCR                NUMDOC  VARCHAR2(20)                                                                               Número de identificação DNI            OPERACIONAL                        NaN
PCMOVCR                NUMSEQ  NUMBER(10,0)                                                          Número sequencial de inserção na tabela PCMOVCR.            OPERACIONAL                        NaN
PCMOVCR          DATACOMPLETA          DATE                                                                    Grava a data completa da movimentação.            OPERACIONAL                        NaN
PCMOVCR         DTESTORNOLANC          DATE                                                                   Data de exclusão de movimentação de DNI            OPERACIONAL                        NaN
PCMOVCR           NUMASSOCDNI  NUMBER(10,0)                                                                   Número de associação de DNI com titulos            OPERACIONAL                        NaN
PCMOVCR      ROTINALANCAMENTO VARCHAR2(100)                                                 Rotina de lançamento do registro (alimentada por trigger)            OPERACIONAL                        NaN
PCMOVCR     ROTINACONCILIACAO VARCHAR2(100)                                         Rotina que fez a conciliação do registro (alimentada por trigger)            OPERACIONAL                        NaN
PCMOVCR     ROTINACOMPENSACAO VARCHAR2(100)                                         Rotina que fez a compensação do registro (alimentada por trigger)            OPERACIONAL                        NaN
PCMOVCR      DTCOMPENSACAOANT          DATE                                                               Data de compensação anterior do lançamento.            OPERACIONAL                        NaN
PCMOVCR           COMPENSACAO   VARCHAR2(2)                                                  Indicador do numerario quanto a estar ou não compensado.            OPERACIONAL                        NaN
PCMOVCR           VLSALDOCOMP  NUMBER(14,2)                                                                                Valor do saldo compensado.            OPERACIONAL                        NaN
PCMOVCR           CODFUNCCOMP   NUMBER(8,0)                                        Matrícula do funcionario que registrou a compensação do numerário.            OPERACIONAL                        NaN
PCMOVCR        CODFUNCALTCOMP   NUMBER(8,0)                                               Matricula do funcionário que alterou a data de compensacao.            OPERACIONAL                        NaN
PCMOVCR      CODPLANOCONTABIL  VARCHAR2(50) Código do plano contábil: Código utilizado na rotina 632 para registrar a mesma informação na rotina 524.            OPERACIONAL                        NaN
PCMOVCR     IDEXTRATOBANCARIO  NUMBER(20,0)                                                              Relação com a Extrato Bancário(IDLANCAMENTO)            OPERACIONAL                        NaN
PCMOVCR       CODFUNCCHECKOUT   NUMBER(8,0)                                                                            Código do funcionário do Caixa            OPERACIONAL                        NaN
PCMOVCR           NUMCHECKOUT   NUMBER(8,0)                                                                                           Número do Caixa            OPERACIONAL                        NaN
PCMOVCR             DTEMISSAO          DATE                                                                                     Data Emissao do Caixa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*