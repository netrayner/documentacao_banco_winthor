# 📊 Tabela: PCITEMLOTECONFERIDO

### Estrutura de Colunas e Restrições

             Tabela                Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMLOTECONFERIDO             CODFILIAL  VARCHAR2(2)                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO                NUMPED NUMBER(10,0)                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO               CODPROD  NUMBER(6,0)                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO               NUMLOTE VARCHAR2(15)                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO                QTCONF NUMBER(20,6)                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO           CODFUNCCONF  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO            CODFUNCSEP  NUMBER(8,0)                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO              DATACONF         DATE                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO           NUMTRANSENT NUMBER(10,0)                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO       PAGTOANTECIPADO  VARCHAR2(1)                                                                 NaN            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO NUMVOLUMESCONFERENCIA  NUMBER(4,0)                 Indica a quantidade de volumes confereido de itens.            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO           CODCERTIFIC  NUMBER(8,0) Indica o código do certif que o lote em conferencia esta vinculado.            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO                NUMCAR  NUMBER(8,0)                                             Número do Carregamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO              NUMCAIXA VARCHAR2(10)                                         Número de caixas conferidas    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO                NUMSEQ NUMBER(20,0)                                                Número de sequencia.    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOTECONFERIDO              QTRESERV NUMBER(21,8)              Quantidade reservada do lote na conferência do pedido.            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO            QTINDUZIDA NUMBER(20,6)                            Quantidade induzida no mapa de separação            OPERACIONAL                        NaN
PCITEMLOTECONFERIDO            DTVALIDADE         DATE                                                       data validade            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*