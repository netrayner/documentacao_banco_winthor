# 📊 Tabela: PCCHEQUEPROPRIO

### Estrutura de Colunas e Restrições

         Tabela         Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCHEQUEPROPRIO      NUMCHEQUE  NUMBER(10,0)                            Número do cheque próprio    CHAVE PRIMÁRIA (PK)                        NaN
PCCHEQUEPROPRIO       NUMTALAO  NUMBER(10,0)                           Número do talão do cheque            OPERACIONAL                        NaN
PCCHEQUEPROPRIO         CODCLI   NUMBER(6,0) Código do cliente pra quem foi direcionado o cheque CHAVE ESTRANGEIRA (FK)                   PCCLIENT
PCCHEQUEPROPRIO     DTCADASTRO          DATE                                    Data de cadastro            OPERACIONAL                        NaN
PCCHEQUEPROPRIO    USUCADASTRO   NUMBER(8,0)                               Usuário que cadastrou            OPERACIONAL                        NaN
PCCHEQUEPROPRIO      DTSUSTADO          DATE                    Data em que o cheque foi sustado            OPERACIONAL                        NaN
PCCHEQUEPROPRIO     USUSUSTADO   NUMBER(8,0)                         Usuário que sustou o cheque            OPERACIONAL                        NaN
PCCHEQUEPROPRIO     DTIMPRESSO          DATE                   Data em que o cheque foi impresso            OPERACIONAL                        NaN
PCCHEQUEPROPRIO    USUIMPRESSO   NUMBER(8,0)                       Usuário que imprimiu o cheque            OPERACIONAL                        NaN
PCCHEQUEPROPRIO    DTUTILIZADO          DATE                  Data em que o cheque foi utilizado            OPERACIONAL                        NaN
PCCHEQUEPROPRIO  NUMTRANSVENDA  NUMBER(10,0)                                  Transação de Venda CHAVE ESTRANGEIRA (FK)                   PCNFSAID
PCCHEQUEPROPRIO         STATUS   VARCHAR2(1)                                  Situação do Cheque            OPERACIONAL                        NaN
PCCHEQUEPROPRIO     OBSERVACAO VARCHAR2(500)                                          Observação            OPERACIONAL                        NaN
PCCHEQUEPROPRIO   IMPRTERCEIRO   VARCHAR2(1)      Indicador se o cheque foi impresso em teceiros            OPERACIONAL                        NaN
PCCHEQUEPROPRIO USUREUTILIZADO   NUMBER(8,0)          Codígo do usuario que reutilizaou o cheque            OPERACIONAL                        NaN
PCCHEQUEPROPRIO  DTREUTILIZADO          DATE                      Data de reutilização do cheque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*