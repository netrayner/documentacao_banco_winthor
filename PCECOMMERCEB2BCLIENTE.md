# 📊 Tabela: PCECOMMERCEB2BCLIENTE

### Estrutura de Colunas e Restrições

               Tabela               Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BCLIENTE            CODFILIAL  VARCHAR2(2)               Código da filial da integração B2B    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BCLIENTE       TIPOINTEGRACAO  NUMBER(4,0)                        Tipo de integração do B2B    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BCLIENTE               CODCLI  NUMBER(6,0)                                Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BCLIENTE           DTINCLUSAO         DATE                                    Data inclusão            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE SITUACAOECOMMERCEB2B  VARCHAR2(3)            Situação do cliente no e-commerce B2B            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE          DTAPROVACAO         DATE           Data de aprovação do limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE     CODFUNCAPROVACAO NUMBER(10,0)  Responsável pela aprovação do limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE         DTREPROVACAO         DATE          Data da reprovação do limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE    CODFUNCREPROVACAO NUMBER(10,0) Responsável pela reprovação do limite de crédito            OPERACIONAL                        NaN
PCECOMMERCEB2BCLIENTE             ROWIDCLI VARCHAR2(50)                    ROWID do registro na PCCLIENT            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*