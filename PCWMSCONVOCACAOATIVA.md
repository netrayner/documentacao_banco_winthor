# 📊 Tabela: PCWMSCONVOCACAOATIVA

### Estrutura de Colunas e Restrições

              Tabela      Coluna Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSCONVOCACAOATIVA DTACEITACAO         DATE      Data aceitação            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA  DTREJEICAO         DATE       Data rejeição            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA   REJEITADA      CHAR(1)           Rejeitada            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA       NUMOS NUMBER(20,0)         Número O.S.            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA      TIPOOS  NUMBER(2,0)           Tipo O.S.            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA   CODMOTIVO  NUMBER(4,0)       Código motivo            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA     CODFUNC  NUMBER(8,0)  Código funcionário            OPERACIONAL                        NaN
PCWMSCONVOCACAOATIVA   CODFILIAL  VARCHAR2(5)       Código filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*