# 📊 Tabela: PCEMPCONSOLIDACAO

### Estrutura de Colunas e Restrições

           Tabela               Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMPCONSOLIDACAO          IDEMPCONSOL  NUMBER(8,0) PK, código incrementado pela sequência DEFSEQ_PCEMPCONSOLIDACAO    CHAVE PRIMÁRIA (PK)                        NaN
PCEMPCONSOLIDACAO            CODFILIAL  VARCHAR2(2)                       Código da filial informada na rotina 2132 CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCEMPCONSOLIDACAO                  ANO  NUMBER(4,0)                                    Ano informado na rotina 2132            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO              CNPJEMP VARCHAR2(14)                                                 CNPJ da empresa            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO            CODIGOEMP VARCHAR2(15)                        Código da empresa informado pelo usuário            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO          RAZAOSOCIAL VARCHAR2(50)                                         Razão social da empresa            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO DTINICIOCONSOLIDACAO         DATE               data de início da consololidação ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO    DTFIMCONSOLIDACAO         DATE                   data final da consololidação ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO      PERCCONSOLIDADO NUMBER(12,4)                   percentual da consololidação ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO              CODPAIS  NUMBER(6,0)                                                  Código do país CHAVE ESTRANGEIRA (FK)                     PCPAIS
PCEMPCONSOLIDACAO    PERCPARTACIONARIA NUMBER(12,4)                           percentual acionária ref. Ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO      DTINIESCRITURAR         DATE                 data de início da escrituração ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO      DTFIMESCRITURAR         DATE                     data final da escrituração ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO  TEMEVENTOSOCIETARIO  VARCHAR2(1)                indica se tem evento societário ref. ano apurado            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO     EVENTOSOCIETARIO  NUMBER(6,0)                                     código do evento societário            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO   DTEVENTOSOCIETARIO         DATE                                       data do evento societário            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO      CONDICAOEMPRESA  NUMBER(6,0)                                             condição da empresa            OPERACIONAL                        NaN
PCEMPCONSOLIDACAO  PERCEMPPARTICIPANTE NUMBER(12,4)                     percentual do participante ref. ano apurado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*