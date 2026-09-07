# 📊 Tabela: PCDESDPREST

### Estrutura de Colunas e Restrições

     Tabela           Coluna Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESDPREST    NUMTRANSVENDA NUMBER(10,0)                                                            Chave de ligação deste registro com a PCPREST.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESDPREST            PREST  VARCHAR2(2)                                                            Chave de ligação deste registro com a PCPREST.    CHAVE PRIMÁRIA (PK)                        NaN
PCDESDPREST           CODCOB  VARCHAR2(4)           Cópia do campo PCPREST.CODCOB da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST          DTCXMOT         DATE          Cópia do campo PCPREST.DTCXMOT da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST          DTFECHA         DATE          Cópia do campo PCPREST.DTFECHA da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST          DTBAIXA         DATE          Cópia do campo PCPREST.DTBAIXA da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST         DTLANCCH         DATE         Cópia do campo PCPREST.DTLANCCH da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST       NUMAGENCIA  NUMBER(4,0)       Cópia do campo PCPREST.NUMAGENCIA da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST        NUMCHEQUE  NUMBER(8,0)        Cópia do campo PCPREST.NUMCHEQUE da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST NUMCONTACORRENTE NUMBER(10,0) Cópia do campo PCPREST.NUMCONTACORRENTE da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST    DTCXMOTHHMMSS         DATE    Cópia do campo PCPREST.DTCXMOTHHMMSS da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST        HORAFECHA  NUMBER(2,0)        Cópia do campo PCPREST.HORAFECHA da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST      MINUTOFECHA  NUMBER(2,0)      Cópia do campo PCPREST.MINUTOFECHA da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST     CODFUNCCXMOT  NUMBER(8,0)     Cópia do campo PCPREST.CODFUNCCXMOT da tabela PCPREST que é sobrescrito no processo de desdobramento.            OPERACIONAL                        NaN
PCDESDPREST     OPERACAODESD VARCHAR2(40)               Campo usado para identificar se o desdobramento é um desdobramento normal ou a maior (1228)            OPERACIONAL                        NaN
PCDESDPREST       QTREPLICAS NUMBER(22,0)         Campo usado pelo processo de cancelar desdobramento para saber quantas vezes o processo foi feito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*