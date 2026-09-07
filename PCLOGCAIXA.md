# 📊 Tabela: PCLOGCAIXA

### Estrutura de Colunas e Restrições

    Tabela             Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCAIXA               DATA          DATE                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA               HORA   NUMBER(2,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA             MINUTO   NUMBER(2,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA           NUMCAIXA   NUMBER(4,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA          CODFUNCCX   NUMBER(8,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA        CODFISCALCX   NUMBER(8,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA             CODCLI   NUMBER(6,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA              VALOR  NUMBER(16,3)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA          HISTORICO VARCHAR2(400)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA           NUMCUPOM  NUMBER(10,0)                                            NaN            OPERACIONAL                        NaN
PCLOGCAIXA          EXPORTADO   VARCHAR2(1)                 Flag se a exportação ocorreu.             OPERACIONAL                        NaN
PCLOGCAIXA       DTEXPORTACAO          DATE Data em que a exportação do BD local ocorreu.             OPERACIONAL                        NaN
PCLOGCAIXA             NUMSEQ  NUMBER(10,0)                          Número de Sequência.             OPERACIONAL                        NaN
PCLOGCAIXA          CODFILIAL   VARCHAR2(2)                             Código da Filial.             OPERACIONAL                        NaN
PCLOGCAIXA MOTIVOCANCELAMENTO VARCHAR2(150)                         Motivo do cancelamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*