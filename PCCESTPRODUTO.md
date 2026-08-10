# 📊 Tabela: PCCESTPRODUTO

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCESTPRODUTO CODCESTPROD NUMBER(10,0)              Código identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCESTPRODUTO  CODSEQCEST  NUMBER(6,0)                    Código do cadastro do CEST CHAVE ESTRANGEIRA (FK)                     PCCEST
PCCESTPRODUTO     CODPROD  NUMBER(6,0)                             Código do produto            OPERACIONAL                        NaN
PCCESTPRODUTO    TIPOPROD  VARCHAR2(1) Tipo do produto (Normal(N) ou Patrimonial(P))            OPERACIONAL                        NaN
PCCESTPRODUTO  DTULTALTER         DATE                      Data de última alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*