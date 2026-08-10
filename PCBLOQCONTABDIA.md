# 📊 Tabela: PCBLOQCONTABDIA

### Estrutura de Colunas e Restrições

         Tabela                 Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQCONTABDIA              CODFILIAL  VARCHAR2(2)                                                        Código da filial            OPERACIONAL                        NaN
PCBLOQCONTABDIA                    ANO  NUMBER(4,0)                                                         Ano do bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABDIA                    MES  NUMBER(2,0)                                                         Mês do bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABDIA                    DIA  NUMBER(2,0)                                                         Dia do bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABDIA              BLOQUEADO  VARCHAR2(1)                                                Indica se está bloqueado            OPERACIONAL                        NaN
PCBLOQCONTABDIA       CODCONFEXERCICIO  NUMBER(8,0)                                                    Código do exercício.            OPERACIONAL                        NaN
PCBLOQCONTABDIA         ROTINABLOQUEIO  NUMBER(4,0)                                                  Código rotina bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABDIA     BLOQUEADO_CONTADOR  VARCHAR2(1) Coluna referente ao bloqueio realizado pelo processo de Perfil Contador            OPERACIONAL                        NaN
PCBLOQCONTABDIA BLOQUEIOPERFILCONTADOR  VARCHAR2(1)     Indica se o dia está bloqueio para o perfil de contador da empresa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*