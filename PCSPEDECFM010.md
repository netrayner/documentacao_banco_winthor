# 📊 Tabela: PCSPEDECFM010

### Estrutura de Colunas e Restrições

       Tabela                 Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM010                     ID   NUMBER(8,0)            Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM010              CODFILIAL   VARCHAR2(2)                    Cód da filial  do lançamento            OPERACIONAL                        NaN
PCSPEDECFM010              EXERCICIO   NUMBER(4,0)                               Ano do lançamento            OPERACIONAL                        NaN
PCSPEDECFM010               CODCONTA  VARCHAR2(30)              Código da conta do plano de contas            OPERACIONAL                        NaN
PCSPEDECFM010              DESCRICAO VARCHAR2(400)                         Descrição do lançamento            OPERACIONAL                        NaN
PCSPEDECFM010              DTCRIACAO          DATE                     Data de criação do registro            OPERACIONAL                        NaN
PCSPEDECFM010         CODCONTAPLANOA   VARCHAR2(7)         Código do lançamento de origem da conta            OPERACIONAL                        NaN
PCSPEDECFM010       DTLIMITEUSODALDO          DATE          Data limite para uso do saldo da conta            OPERACIONAL                        NaN
PCSPEDECFM010            TIPOTRIBUTO       CHAR(1)              I=Imposto de Renda Pessoa Jurídica            OPERACIONAL                        NaN
PCSPEDECFM010           SALDOINICIAL  NUMBER(22,4)                                   Saldo inicial            OPERACIONAL                        NaN
PCSPEDECFM010                  SINAL       CHAR(1)                       D = débito ou C = Crédito            OPERACIONAL                        NaN
PCSPEDECFM010                   CNPJ  VARCHAR2(18)                         CNPJ da empresa credora            OPERACIONAL                        NaN
PCSPEDECFM010                  LALUR       CHAR(1)                           S = LALUR ou N = LACS            OPERACIONAL                        NaN
PCSPEDECFM010         CODCONTAPLANOB  VARCHAR2(10)             Código do plano de conta ECF tipo B            OPERACIONAL                        NaN
PCSPEDECFM010      DTLIMITEUSODALDOB          DATE Data limite de uso da conta do plano de conta B            OPERACIONAL                        NaN
PCSPEDECFM010           TIPOTRIBUTOB   VARCHAR2(1)    Tipo de tributo da conta do plano de conta B            OPERACIONAL                        NaN
PCSPEDECFM010 DESCRICAO_CONTA_PLANOB VARCHAR2(500)   Descrição da conta do plano de conta B do ECF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*