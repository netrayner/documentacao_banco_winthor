# 📊 Tabela: PCSPEDECFLANCAMENTO

### Estrutura de Colunas e Restrições

             Tabela                 Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFLANCAMENTO                     ID        NUMBER                      Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFLANCAMENTO          IDPLANOCONTAS   NUMBER(8,0)     Identificador da conta no plano de contas do SPED ECF            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO              CODFILIAL   VARCHAR2(2)                              Cód. da filial do lançamento            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO              HISTORICO VARCHAR2(200)                        Motivo ou finalidade do lançamento            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO            TIPOPERIODO       CHAR(1)               T = período trimestral ou A = período anual            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO            PERIODOLANC   NUMBER(2,0) 1 a 4 para período trimestral e 1 a 12 para período anual            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO                    ANO   NUMBER(4,0)                                         Ano do lançamento            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO              DTCRIACAO          DATE             Data da criação do registro no banco de dados            OPERACIONAL                        NaN
PCSPEDECFLANCAMENTO PREENCHIMENTOINCORRETO       CHAR(1)                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*