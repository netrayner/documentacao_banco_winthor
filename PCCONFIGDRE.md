# 📊 Tabela: PCCONFIGDRE

### Estrutura de Colunas e Restrições

     Tabela           Coluna   Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGDRE        CODCONFIG    NUMBER(5,0)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE            ORDEM    NUMBER(3,0)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE    DESC_OPERACAO   VARCHAR2(60)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE            REGRA  VARCHAR2(100)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE     CODCONFIGPAI    NUMBER(5,0)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE    TIPORESULTADO    VARCHAR2(1)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE      VALORMANUAL   NUMBER(12,2)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE   DESC_RESULTADO VARCHAR2(4000)                                                                   NaN            OPERACIONAL                        NaN
PCCONFIGDRE CODCONTAREDUZIDO   VARCHAR2(12)                                              Código da conta reduzido            OPERACIONAL                        NaN
PCCONFIGDRE       CODDEMONST    NUMBER(6,0) . Faz relacionamento com o demonstrativo a qual as regras pertencem.             OPERACIONAL                        NaN
PCCONFIGDRE     BASEVERTICAL    VARCHAR2(1)                                 Indica o grupo para análise vertical.            OPERACIONAL                        NaN
PCCONFIGDRE    CODPLANOCONTA    NUMBER(5,0)                                   Indica o código do plano de contas.            OPERACIONAL                        NaN
PCCONFIGDRE     NATUREZALANC    VARCHAR2(1)                                    Considera ST NF no Custo Contábil.            OPERACIONAL                        NaN
PCCONFIGDRE         SALDODFC    NUMBER(1,0)                                  Considera ST Guia no Custo Contábil.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*