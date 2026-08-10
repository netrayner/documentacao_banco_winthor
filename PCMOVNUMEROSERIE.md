# 📊 Tabela: PCMOVNUMEROSERIE

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVNUMEROSERIE           CODFILIAL  VARCHAR2(2)                    Código da filial            OPERACIONAL                        NaN
PCMOVNUMEROSERIE             CODPROD  NUMBER(6,0)                   Código do produto            OPERACIONAL                        NaN
PCMOVNUMEROSERIE            NUMSERIE VARCHAR2(60)                     Número de série            OPERACIONAL                        NaN
PCMOVNUMEROSERIE NUMTRANSNUMEROSERIE NUMBER(10,0) Número da transação de movimentação            OPERACIONAL                        NaN
PCMOVNUMEROSERIE  DATAMOVNUMEROSERIE         DATE                Data de movimentação            OPERACIONAL                        NaN
PCMOVNUMEROSERIE            BLOQUEIO  VARCHAR2(1)                            Bloqueio            OPERACIONAL                        NaN
PCMOVNUMEROSERIE              AVARIA  VARCHAR2(1)                              Avaria            OPERACIONAL                        NaN
PCMOVNUMEROSERIE           CONFERIDO  VARCHAR2(1)   ITEM DE NÚMERO DE SÉRIE CONFERIDO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*