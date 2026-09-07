# 📊 Tabela: PCMOVCRFOR

### Estrutura de Colunas e Restrições

    Tabela                   Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVCRFOR            NUMTRANSCRFOR  NUMBER(6,0)                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVCRFOR                CODFILIAL  VARCHAR2(2)                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVCRFOR                     DATA         DATE                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                CODFORNEC  NUMBER(6,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                TIPOVERBA  VARCHAR2(1)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                    VALOR NUMBER(18,6)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                     TIPO  VARCHAR2(1)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR               HISTORICO1 VARCHAR2(80)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR               HISTORICO2 VARCHAR2(80)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR               HISTORICO3 VARCHAR2(80)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR               HISTORICO4 VARCHAR2(80)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                 NUMVERBA  NUMBER(8,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                NUMPEDIDO  NUMBER(8,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                  VLSALDO NUMBER(16,2)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                     HORA  NUMBER(2,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                   MINUTO  NUMBER(2,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                  CODFUNC  NUMBER(8,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                 DTCONCIL         DATE                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR              CONCILIACAO  VARCHAR2(2)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                DTESTORNO         DATE                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR              NUMTRANSEST  NUMBER(8,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR            VLSALDOCONCIL NUMBER(14,2)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                 SALDOTMP NUMBER(14,2)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR            CODBANCOBAIXA  NUMBER(4,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR            CODMOEDABAIXA  VARCHAR2(4)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                  NUMLANC  NUMBER(8,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR     NUMTRANSENTDEVFORNEC NUMBER(10,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR              NUMTRANSENT NUMBER(10,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR                 CODCONTA NUMBER(10,0)                          Indica a rotina de lançamento.             OPERACIONAL                        NaN
PCMOVCRFOR               ROTINALANC  NUMBER(6,0)                                                      NaN            OPERACIONAL                        NaN
PCMOVCRFOR               CODFUNCCAN  NUMBER(8,0)             Indica o código do funcionário que cancelou.            OPERACIONAL                        NaN
PCMOVCRFOR             CODTIPOVERBA NUMBER(10,0)                       Indica o código do tipo de verba.             OPERACIONAL                        NaN
PCMOVCRFOR                   ORIGEM  VARCHAR2(1)                  Indica a origem do lançamento da verba.            OPERACIONAL                        NaN
PCMOVCRFOR            DTCOMPETENCIA         DATE  Data de competência da conciliação de baixa de verbas.             OPERACIONAL                        NaN
PCMOVCRFOR                   DTPAGO         DATE                           Gravar data de pagamento verba            OPERACIONAL                        NaN
PCMOVCRFOR               LANCAVULSO  VARCHAR2(1)                                        Lançamento avulso            OPERACIONAL                        NaN
PCMOVCRFOR           CODFORNECPRINC  NUMBER(6,0)                  Indica o código principal no fornecedor            OPERACIONAL                        NaN
PCMOVCRFOR                EQUIPLANC VARCHAR2(64)                          Máquina de inclusão do registro            OPERACIONAL                        NaN
PCMOVCRFOR                 FUNCLANC VARCHAR2(30)                    Usuário da rede inclusão do resgistro            OPERACIONAL                        NaN
PCMOVCRFOR                ROTINACAD VARCHAR2(48)                               Nome da rotina de inclusão            OPERACIONAL                        NaN
PCMOVCRFOR      NUMTRANSCRFORORIGEM  NUMBER(6,0)             Numero de transação do conta corrente origem            OPERACIONAL                        NaN
PCMOVCRFOR            DESCFINAVULSO  VARCHAR2(1)   Define se o lançamento avulso é de desconto financeiro            OPERACIONAL                        NaN
PCMOVCRFOR                 BAIXADNI  VARCHAR2(1)                           Identificador de baixa por DNI            OPERACIONAL                        NaN
PCMOVCRFOR CODCONTAFUNDOMULTIFILIAL NUMBER(10,0) Campo para gravar o codigo da conta do fundo multifilial            OPERACIONAL                        NaN
PCMOVCRFOR             CODCOMPRADOR  NUMBER(8,0)                 Campo para gravaro o código do comprador            OPERACIONAL                        NaN
PCMOVCRFOR                  DATALOG         DATE            Campo para gravar data e hora da movimentação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*