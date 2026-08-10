# 📊 Tabela: PCBLOQCONTABMES

### Estrutura de Colunas e Restrições

         Tabela             Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBLOQCONTABMES          CODFILIAL  VARCHAR2(2)                                                        Código da filial            OPERACIONAL                        NaN
PCBLOQCONTABMES                ANO  NUMBER(4,0)                                                         Ano do bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABMES                MES  NUMBER(2,0)                                                         Mês do bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABMES          BLOQUEADO  VARCHAR2(1)                                                Indica se está bloqueado            OPERACIONAL                        NaN
PCBLOQCONTABMES   CODCONFEXERCICIO  NUMBER(8,0)                                                    Código do exercício.            OPERACIONAL                        NaN
PCBLOQCONTABMES     ROTINABLOQUEIO  NUMBER(4,0)                                                  Código rotina bloqueio            OPERACIONAL                        NaN
PCBLOQCONTABMES BLOQUEADO_CONTADOR  VARCHAR2(1) Coluna referente ao bloqueio realizado pelo processo de Perfil Contador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*