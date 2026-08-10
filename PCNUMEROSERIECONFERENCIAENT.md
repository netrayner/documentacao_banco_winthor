# 📊 Tabela: PCNUMEROSERIECONFERENCIAENT

### Estrutura de Colunas e Restrições

                     Tabela       Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNUMEROSERIECONFERENCIAENT IDLINHAPCMOV VARCHAR2(50)                             ROWID da PCMOV    CHAVE PRIMÁRIA (PK)                        NaN
PCNUMEROSERIECONFERENCIAENT     NUMSERIE VARCHAR2(60)                            Número de série    CHAVE PRIMÁRIA (PK)                        NaN
PCNUMEROSERIECONFERENCIAENT     AVARIADO  VARCHAR2(1) Informa se o número de série esta avariado            OPERACIONAL                        NaN
PCNUMEROSERIECONFERENCIAENT       NUMSEQ NUMBER(20,0)   Numero sequencial do item do recebimento            OPERACIONAL                        NaN
PCNUMEROSERIECONFERENCIAENT    CODMOTIVO  NUMBER(4,0)        Código do motivo de avaria da série            OPERACIONAL                        NaN
PCNUMEROSERIECONFERENCIAENT   DTVALIDADE         DATE                 Data de validade informada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*