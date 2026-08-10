# 📊 Tabela: PCRECEBIMENTOFV

### Estrutura de Colunas e Restrições

         Tabela           Coluna   Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECEBIMENTOFV        NUMPEDRCA   NUMBER(10,0)                                               Numero do pedido do palm    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEBIMENTOFV          CODUSUR    NUMBER(4,0)                                                Codigo do RCA do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEBIMENTOFV    NUMTRANSVENDA   NUMBER(10,0)                                   Numtranvenda gerado pelo faturamento            OPERACIONAL                        NaN
PCRECEBIMENTOFV   NUMRECEBIMENTO    NUMBER(2,0)                                                  Numero do recebimento    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEBIMENTOFV           CODCLI    NUMBER(6,0)                                                      Codigo do cliente            OPERACIONAL                        NaN
PCRECEBIMENTOFV            PREST    VARCHAR2(2)                                                 Parcela do recebimento    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEBIMENTOFV           DUPLIC   NUMBER(10,0)                                               Numero da nota do pedido            OPERACIONAL                        NaN
PCRECEBIMENTOFV            VALOR   NUMBER(10,2)                                                   Valor do recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV           CODCOB    VARCHAR2(4)                                      Codigo de cobrança do recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV        CODFILIAL    VARCHAR2(2)                                                       Codigo da Filial            OPERACIONAL                        NaN
PCRECEBIMENTOFV         NUMBANCO    NUMBER(4,0)                                                        Numero do banco            OPERACIONAL                        NaN
PCRECEBIMENTOFV       NUMAGENCIA    NUMBER(4,0)                                                      Numero da agencia            OPERACIONAL                        NaN
PCRECEBIMENTOFV        NUMCHEQUE    NUMBER(8,0)                                                       Numero do Cheque            OPERACIONAL                        NaN
PCRECEBIMENTOFV              OBS   VARCHAR2(20)                                                             observação            OPERACIONAL                        NaN
PCRECEBIMENTOFV             OBS2   VARCHAR2(60)                                                           Observação 2            OPERACIONAL                        NaN
PCRECEBIMENTOFV       CODFUNCINC    NUMBER(8,0)                        Codigo do Funcionario que incluiu o recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV         CODBANCO    NUMBER(4,0)                                                        Codigo do banco            OPERACIONAL                        NaN
PCRECEBIMENTOFV NUMCONTACORRENTE   NUMBER(10,0)                                               Numero da conta corrente            OPERACIONAL                        NaN
PCRECEBIMENTOFV         CGCCPFCH   VARCHAR2(18)                                          Cgc/Cpf do emitente do cheque            OPERACIONAL                        NaN
PCRECEBIMENTOFV        DVAGENCIA    NUMBER(1,0)                                          Digito verificador da agencia            OPERACIONAL                        NaN
PCRECEBIMENTOFV         DVCHEQUE    NUMBER(1,0)                                           Digito verificador do cheque            OPERACIONAL                        NaN
PCRECEBIMENTOFV          DVCONTA    NUMBER(1,0)                                            Digito verificador da conta            OPERACIONAL                        NaN
PCRECEBIMENTOFV       DTINCLUSAO           DATE                                        Data de inclsuao do recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV        DTEMISSAO           DATE                                         Data de emissao do recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV           DTVENC           DATE                                      Data de vencimento do recebimento            OPERACIONAL                        NaN
PCRECEBIMENTOFV    NOSSONUMBANCO   VARCHAR2(30)                                                                    NaN            OPERACIONAL                        NaN
PCRECEBIMENTOFV         CODBARRA   VARCHAR2(44)                                                       Codigo de barras            OPERACIONAL                        NaN
PCRECEBIMENTOFV         LINHADIG   VARCHAR2(65)                                                                    NaN            OPERACIONAL                        NaN
PCRECEBIMENTOFV       VERIFICADO    NUMBER(1,0)                                                  Controle de validação            OPERACIONAL                        NaN
PCRECEBIMENTOFV    OBSERVACAO_PC VARCHAR2(4000)                                               Observação da importação            OPERACIONAL                        NaN
PCRECEBIMENTOFV           NUMCAR    NUMBER(8,0)                                                 Nùmero do Carregamento            OPERACIONAL                        NaN
PCRECEBIMENTOFV   COMPENSACAOBCO    NUMBER(3,0)                                              Banco Compensão do cheque            OPERACIONAL                        NaN
PCRECEBIMENTOFV           TXPERM   NUMBER(10,2)                                Sentido reversoJUROS RECEBIDOS PELO RCA            OPERACIONAL                        NaN
PCRECEBIMENTOFV        CANCELADO    VARCHAR2(1) INDICA SE O DESDOBRAMENTO FOI OU NÃO CANCELADO PELO RCA (S=SIM, N=NAO)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*