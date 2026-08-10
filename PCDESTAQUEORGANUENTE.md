# 📊 Tabela: PCDESTAQUEORGANUENTE

### Estrutura de Colunas e Restrições

              Tabela          Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESTAQUEORGANUENTE      IDDESTAQUE  VARCHAR2(8)           Código do Orgãos Anuentes    CHAVE PRIMÁRIA (PK)                 PCDESTAQUE
PCDESTAQUEORGANUENTE CODORGAOANUENTE  VARCHAR2(8)        Descrição do Orgãos Anuentes    CHAVE PRIMÁRIA (PK)             PCORGAOANUENTE
PCDESTAQUEORGANUENTE      DTCADASTRO         DATE                     Data do Vinculo            OPERACIONAL                        NaN
PCDESTAQUEORGANUENTE      CODUSUARIO  NUMBER(8,0) Código do usuário que fez o finculo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*