# 📊 Tabela: PCBLOQUEIOSPEDIDO

### Estrutura de Colunas e Restrições

           Tabela         Coluna  Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQUEIOSPEDIDO         CODIGO  NUMBER(10,0)                                                   Código sequencial            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO         NUMPED  NUMBER(10,0)                                                    Numero do pedido            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO      CODMOTIVO   NUMBER(6,0)                                                    Codigo do motivo            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO CODMOTBLOQUEIO   NUMBER(8,0)                                         Código motivo da rotina 307            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO         MOTIVO VARCHAR2(200)                                                 Descrição do motivo            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO         STATUS   VARCHAR2(1)                                            B =Bloqueado,L= Liberado            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO           TIPO   VARCHAR2(1)                                          C =Comercial,F= Financeiro            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO  CODFUNCLIBERA   NUMBER(8,0) Código do funcionário que efetuou a liberação do motivo de bloqueio            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO       DTLIBERA          DATE                          Data da liberação deste motivo de bloqueio            OPERACIONAL                        NaN
PCBLOQUEIOSPEDIDO     DTINCLUSAO          DATE      Indica a data e hora que foi inserido o bloqueio para o pedido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*