# 📊 Tabela: PCINDC

### Estrutura de Colunas e Restrições

Tabela          Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDC      NUMINDENIZ NUMBER(10,0)                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDC            DATA         DATE                                                                  NaN            OPERACIONAL                        NaN
PCINDC         VLTOTAL NUMBER(12,2)                                                                  NaN            OPERACIONAL                        NaN
PCINDC          CODCLI  NUMBER(6,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC       CODFILIAL  VARCHAR2(2)                                                                  NaN            OPERACIONAL                        NaN
PCINDC         TOTPESO NUMBER(12,3)                                                                  NaN            OPERACIONAL                        NaN
PCINDC       TOTVOLUME NUMBER(12,4)                                                                  NaN            OPERACIONAL                        NaN
PCINDC        NUMITENS  NUMBER(4,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC     CODEMITENTE  NUMBER(8,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC         NUMNOTA NUMBER(10,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC         POSICAO  VARCHAR2(1)                                                                  NaN            OPERACIONAL                        NaN
PCINDC          NUMPED NUMBER(10,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC     TIPOINDENIZ  VARCHAR2(1)                                                                  NaN            OPERACIONAL                        NaN
PCINDC         CODUSUR  NUMBER(4,0)                                                                  NaN            OPERACIONAL                        NaN
PCINDC         DTDEVOL         DATE                             Data da Devolução da troca/indenização.             OPERACIONAL                        NaN
PCINDC    CODFUNCDEVOL  NUMBER(8,0) Código do Funcionário que efetuou a Devolução da troca/indenização.             OPERACIONAL                        NaN
PCINDC      DTEXCLUSAO         DATE                              Data da Exclusão da troca/indenização.             OPERACIONAL                        NaN
PCINDC CODFUNCEXCLUSAO  NUMBER(8,0)  Código do Funcionário que efetuou a Exclusão da troca/indenização.             OPERACIONAL                        NaN
PCINDC          NUMCAR  NUMBER(8,0)                                     Indica o numero do carregamento.            OPERACIONAL                        NaN
PCINDC             OBS VARCHAR2(80)                                  Indica a observação da indenização.            OPERACIONAL                        NaN
PCINDC      DTMXSALTER         DATE                                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*