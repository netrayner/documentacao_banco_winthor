# 📊 Tabela: PCINVENTITENS

### Estrutura de Colunas e Restrições

       Tabela      Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTITENS     CODPROD  NUMBER(6,0)   Código do produto inventariado    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTITENS CODENDERECO  NUMBER(8,0)    Código do endereço do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTITENS   NUMINVENT NUMBER(10,0)             Número do inventário    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTITENS    INVENTOS NUMBER(10,0) Número da OS usado no inventário            OPERACIONAL                        NaN
PCINVENTITENS  DTINCLUSAO         DATE                 Data de inclusão            OPERACIONAL                        NaN
PCINVENTITENS   MATRICULA NUMBER(10,0)              Usuário que incluiu            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*