# 📊 Tabela: PCHISTNOSSONUMEROBCO

### Estrutura de Colunas e Restrições

              Tabela             Coluna  Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTNOSSONUMEROBCO               DATA          DATE                               Data e hora da gravação            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO            USUARIO VARCHAR2(100)                      Usuário que realizou a alteração            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO            MAQUINA VARCHAR2(100)           Máquina do usuário que realizou a alteração            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO             ROTINA VARCHAR2(100)                       Rotina que realizou a alteração            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO      NUMTRANSVENDA  NUMBER(10,0)                          Número de transação da prest            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO              PREST   VARCHAR2(2) Valor da prest que alterou informação do nosso número            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO             CODCLI   NUMBER(6,0)                             Cliente associado a prest            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO               TIPO  VARCHAR2(20)                             Tipo(Geração / Alteração)            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO  NOSSONUMEROANTIGO  VARCHAR2(30)                        Valor do nosso número anterior            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO    NOSSONUMERONOVO  VARCHAR2(30)                           Valor do nosso número atual            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO NOSSONUMERO2ANTIGO  VARCHAR2(30)                        Valor do nosso número anterior            OPERACIONAL                        NaN
PCHISTNOSSONUMEROBCO   NOSSONUMERO2NOVO  VARCHAR2(30)                           Valor do nosso número atual            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*