# 📊 Tabela: PCAGENDAFORNEC

### Estrutura de Colunas e Restrições

        Tabela           Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAFORNEC        CODFORNEC   NUMBER(6,0)                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC     CODCOMPRADOR   NUMBER(8,0)                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC    PERIODICIDADE   NUMBER(4,0)                                         NaN            OPERACIONAL                        NaN
PCAGENDAFORNEC        DIASEMANA   NUMBER(2,0)                                         NaN            OPERACIONAL                        NaN
PCAGENDAFORNEC  DTPROXIMAVISITA          DATE                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC              OBS VARCHAR2(100)                                         NaN            OPERACIONAL                        NaN
PCAGENDAFORNEC       HORAVISITA   NUMBER(2,0)                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC     MINUTOVISITA   NUMBER(2,0)                                         NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC USAPERIODICIDADE   VARCHAR2(1)                 Usa agenda por periocidade.            OPERACIONAL                        NaN
PCAGENDAFORNEC        CODFILIAL   VARCHAR2(2) Apresenta o código da filial do agendamento    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAFORNEC    HORAVISITAFIM   NUMBER(2,0)                                         NaN            OPERACIONAL                        NaN
PCAGENDAFORNEC  MINUTOVISITAFIM   NUMBER(2,0)                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*