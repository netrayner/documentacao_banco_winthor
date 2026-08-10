# 📊 Tabela: PCLOGTRANSFNFCARREG

### Estrutura de Colunas e Restrições

             Tabela         Coluna  Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGTRANSFNFCARREG        NUMNOTA  NUMBER(10,0)                                    Indica o número da nota.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG    NUMCARATUAL  NUMBER(10,0)                      Indica o número do carregamento atual.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG NUMCARANTERIOR  NUMBER(10,0)                   Indica o número do carregamento anterior.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG  NUMTRANSVENDA  NUMBER(10,0)                         Indica o número da transição da NF.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG       DTTRANSF          DATE                     Indica a data de transferência das NFs.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG   MOTIVOTRANSF VARCHAR2(200)                   Indica o motivo da transferência das NFs.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG  CODFILIALORIG   VARCHAR2(2)                           Indica o código da filial origem.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG  CODFILIALDEST   VARCHAR2(2)                          Indica o código da filial destino.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG         NUMPED  NUMBER(10,0)                      Indica o número do pedido transferido.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG  CODFUNCTRANSF   NUMBER(8,0) Indica o código do funcionário que efetuou a transferência.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG      CODMOTIVO   NUMBER(4,0)                 Indica o código do motivo de transferência.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG        MAQUINA  VARCHAR2(80)        Nome da máquina na rede que efetuou a transferência.            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG    IDSOFITVIEW  VARCHAR2(10)                      Indica o código da viagem na SofitView            OPERACIONAL                        NaN
PCLOGTRANSFNFCARREG     OBSERVACAO VARCHAR2(200)               Indica a observação da transferência das NFs.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*