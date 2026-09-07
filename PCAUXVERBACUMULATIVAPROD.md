# 📊 Tabela: PCAUXVERBACUMULATIVAPROD

### Estrutura de Colunas e Restrições

                  Tabela          Coluna  Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUXVERBACUMULATIVAPROD            DATA          DATE                                   Data de inserção do campo na tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD          NUMPED  NUMBER(10,0)                                                      Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD         CODPROD   NUMBER(6,0)                                                     Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD          NUMSEQ  NUMBER(20,0)                                 Número de sequência do item no pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD     NUMVERBACMV   NUMBER(8,0)                             Número da verba cadastrada na rotina 1801    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD      VLVERBACMV  NUMBER(18,6)                                Valor da verba encontrada na validação    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD     ORIGEMVERBA   NUMBER(6,0) Rotina cuja verba foi vinculada(1831,301, 357, 561, 3306, 3307, 3320)            OPERACIONAL                        NaN
PCAUXVERBACUMULATIVAPROD        PROGRAMA VARCHAR2(100)                   Rotina que solicitou a inclusão dos dados na tabela            OPERACIONAL                        NaN
PCAUXVERBACUMULATIVAPROD             SEQ  NUMBER(20,0)                              Ordem de inserção dos dados nesta tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXVERBACUMULATIVAPROD DTAPURACAOVERBA          DATE                              Data da apuração gerada pela rotina 1832            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*