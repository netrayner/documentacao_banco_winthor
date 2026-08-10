# 📊 Tabela: PCETQFORNEC

### Estrutura de Colunas e Restrições

     Tabela    Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCETQFORNEC        ID        NUMBER                     Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCETQFORNEC CODFORNEC   NUMBER(6,0)                    Codigo do fornecedor CHAVE ESTRANGEIRA (FK)                   PCFORNEC
PCETQFORNEC DESCRICAO VARCHAR2(100) Descrição para identificação do usuário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*