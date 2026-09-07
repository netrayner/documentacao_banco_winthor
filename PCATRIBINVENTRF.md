# 📊 Tabela: PCATRIBINVENTRF

### Estrutura de Colunas e Restrições

         Tabela     Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCATRIBINVENTRF  NUMINVENT  NUMBER(8,0)                  Número do inventário            OPERACIONAL                        NaN
PCATRIBINVENTRF    MATCONT  NUMBER(8,0)                 Matrícula do contador            OPERACIONAL                        NaN
PCATRIBINVENTRF   CONTAGEM VARCHAR2(20)                    Número da contagem            OPERACIONAL                        NaN
PCATRIBINVENTRF   CODLOCAL VARCHAR2(20)                       Código do local            OPERACIONAL                        NaN
PCATRIBINVENTRF  DTINICONT         DATE            Data de início da contagem            OPERACIONAL                        NaN
PCATRIBINVENTRF  DTFIMCONT         DATE                Data final da contagem            OPERACIONAL                        NaN
PCATRIBINVENTRF ATUALIZADO  VARCHAR2(1) Se o inventario foi ou não atualizado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*