# 📊 Tabela: PCSPEDECFM300

### Estrutura de Colunas e Restrições

       Tabela              Coluna Tipo/Tamanho                                                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM300                  ID NUMBER(22,0)                                                                                             Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM300        IDLANCAMENTO       NUMBER                                                                                                 ID da tabela PCSPEDECFLANCAMENTO CHAVE ESTRANGEIRA (FK)        PCSPEDECFLANCAMENTO
PCSPEDECFM300               VALOR NUMBER(22,4)                                                                                                              Valor do lançamento            OPERACIONAL                        NaN
PCSPEDECFM300              ORIGEM      CHAR(1) M=Manual, F=Fórmula, S=Saldo, L=Lançamento. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300 ORIGEMCODPLANOCONTA NUMBER(22,0)           Cód do plano de contas de origem. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300      ORIGEMCODCONTA VARCHAR2(12)                     Cód da conta de origem. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300           ORIGEMSEQ NUMBER(22,0)                    Sequência do lançamento. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300     ORIGEMNUMLANCTO NUMBER(22,0)                           Nº do lançamento. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300           ORIGEMMES NUMBER(22,0)                          Mês do lançamento. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300           ORIGEMANO NUMBER(22,0)                          Ano do lançamento. Preencher quando incluir Lançamento de contas ou Saldo de contas na parte A do LALUR            OPERACIONAL                        NaN
PCSPEDECFM300               LALUR      CHAR(1)                                                                                                            S = LALUR ou N = LACS            OPERACIONAL                        NaN
PCSPEDECFM300           DTCRIACAO         DATE                                                                                    Data de criação do registro no banco de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*