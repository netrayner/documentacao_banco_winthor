# 📊 Tabela: PCPLANOCONTACONSOLIDACAO

### Estrutura de Colunas e Restrições

                  Tabela         Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLANOCONTACONSOLIDACAO IDPLACONCONSOL  NUMBER(8,0) PK, código incrementado pela sequência DFSEQ_PCPLANOCONTACONSOL    CHAVE PRIMÁRIA (PK)                        NaN
PCPLANOCONTACONSOLIDACAO    IDEMPCONSOL  NUMBER(8,0)      FK Código da empresa referência a tabela PCEMPCONSOLIDACAO CHAVE ESTRANGEIRA (FK)          PCEMPCONSOLIDACAO
PCPLANOCONTACONSOLIDACAO      CODFILIAL  VARCHAR2(2)                       Código da filial informada na rotina 2132            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO            ANO  NUMBER(4,0)                                    Ano informado na rotina 2132            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO        CNPJEMP VARCHAR2(14)                                                 CNPJ da empresa            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO       CODCONTA VARCHAR2(20)                                       Código analítico da conta            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO      DESCCONTA VARCHAR2(50)                                              Descrição da conta            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO  NATUREZACONTA  VARCHAR2(1)                                         natureza da conta (C/D)            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO          SALDO NUMBER(12,2)                                                  Saldo da conta            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO  NATUREZASALDO  VARCHAR2(1)                                         natureza do saldo (C/D)            OPERACIONAL                        NaN
PCPLANOCONTACONSOLIDACAO  CODPLANOCONTA  NUMBER(5,0)                                       Código do plano de contas CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PCPLANOCONTACONSOLIDACAO CODREDUZIDO_PC VARCHAR2(12)                                Código reduzido da conta WinThor CHAVE ESTRANGEIRA (FK)                 PCMODELOPC

---
*Documentação gerada automaticamente.*