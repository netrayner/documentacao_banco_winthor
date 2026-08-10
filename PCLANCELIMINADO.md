# 📊 Tabela: PCLANCELIMINADO

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLANCELIMINADO IDLANCELIMINADO  NUMBER(8,0)              PK, código incrementado pela sequência DFSEQ_PCLANCELIMINADO            OPERACIONAL                        NaN
PCLANCELIMINADO  IDPLACONCONSOL  NUMBER(8,0) FK Código do plano de contas referência a tabela PCPLANOCONTACONSOLIDACAO            OPERACIONAL                        NaN
PCLANCELIMINADO       CODFILIAL  VARCHAR2(2)                                 Código da filial informada na rotina 2132            OPERACIONAL                        NaN
PCLANCELIMINADO             ANO  NUMBER(4,0)                                              Ano informado na rotina 2132            OPERACIONAL                        NaN
PCLANCELIMINADO         CNPJEMP VARCHAR2(14)                                                           CNPJ da empresa            OPERACIONAL                        NaN
PCLANCELIMINADO        CODCONTA VARCHAR2(20)                                                 Código analítico da conta            OPERACIONAL                        NaN
PCLANCELIMINADO           VALOR NUMBER(12,2)                                                            Saldo da conta            OPERACIONAL                        NaN
PCLANCELIMINADO        NATUREZA  VARCHAR2(1)                                                   natureza do saldo (C/D)            OPERACIONAL                        NaN
PCLANCELIMINADO     IDEMPCONSOL  NUMBER(8,0)                                            Código da empresa participante CHAVE ESTRANGEIRA (FK)          PCEMPCONSOLIDACAO
PCLANCELIMINADO   CODPLANOCONTA  NUMBER(5,0)                                                 Código do plano de contas CHAVE ESTRANGEIRA (FK)                 PCMODELOPC
PCLANCELIMINADO  CODREDUZIDO_PC VARCHAR2(12)                                                  Código reduzido da conta CHAVE ESTRANGEIRA (FK)                 PCMODELOPC

---
*Documentação gerada automaticamente.*