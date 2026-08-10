# 📊 Tabela: PCLOGALTCLI

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGALTCLI   MATRICULA  NUMBER(8,0)                                             NaN            OPERACIONAL                        NaN
PCLOGALTCLI      CODCLI  NUMBER(6,0)                                             NaN            OPERACIONAL                        NaN
PCLOGALTCLI DTALTERACAO         DATE                                             NaN            OPERACIONAL                        NaN
PCLOGALTCLI      ROTINA VARCHAR2(40)                                          Rotina            OPERACIONAL                        NaN
PCLOGALTCLI         OBS VARCHAR2(40)                                     Observação.            OPERACIONAL                        NaN
PCLOGALTCLI       CAMPO VARCHAR2(30)                    Nome campo que foi alterado.            OPERACIONAL                        NaN
PCLOGALTCLI    VALORANT         CLOB     Valor anterior do campo antes da alteração.            OPERACIONAL                        NaN
PCLOGALTCLI    VALORATU         CLOB                           Valor atual do campo.            OPERACIONAL                        NaN
PCLOGALTCLI     CODFUNC  NUMBER(8,0) Código do funcionario que realizou a alteração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*