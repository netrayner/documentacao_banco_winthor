# 📊 Tabela: PCSNGPCHIST

### Estrutura de Colunas e Restrições

     Tabela     Coluna Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSNGPCHIST  CODFILIAL  VARCHAR2(2)                                                                     Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCSNGPCHIST     DTOPER         DATE                                                                     Data da Operação    CHAVE PRIMÁRIA (PK)                        NaN
PCSNGPCHIST    SEQOPER  NUMBER(2,0)                                                                Sequência da Operação    CHAVE PRIMÁRIA (PK)                        NaN
PCSNGPCHIST    TIPOPER  VARCHAR2(1) Tipo de Operação [M-Movimentações;C-Confirmação Inventário;F-Finalização Inventário]            OPERACIONAL                        NaN
PCSNGPCHIST   DTINIMOV         DATE                                                       Data Inicial das Movimentações            OPERACIONAL                        NaN
PCSNGPCHIST   DTFINMOV         DATE                                                         Data Final das Movimentações            OPERACIONAL                        NaN
PCSNGPCHIST  MATRICULA  NUMBER(8,0)                         Matrícula do usuário responsável pelo processamento do SNGPC            OPERACIONAL                        NaN
PCSNGPCHIST  STATUSXML  NUMBER(1,0)                                                     Status do XML [1-Gerado Arquivo]            OPERACIONAL                        NaN
PCSNGPCHIST NOMEARQXML VARCHAR2(50)                                                                  Nome do Arquivo XML            OPERACIONAL                        NaN
PCSNGPCHIST      DTEXP         DATE                                                                      Data Exportação            OPERACIONAL                        NaN
PCSNGPCHIST     SEQEXP NUMBER(10,0)                                                              Sequência de Exportação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*