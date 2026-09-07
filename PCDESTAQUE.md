# 📊 Tabela: PCDESTAQUE

### Estrutura de Colunas e Restrições

    Tabela     Coluna  Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESTAQUE IDDESTAQUE   VARCHAR2(8)         Código do destaque    CHAVE PRIMÁRIA (PK)                        NaN
PCDESTAQUE  DESCRICAO VARCHAR2(100)      Descrição do destaque            OPERACIONAL                        NaN
PCDESTAQUE DTCADASTRO          DATE            Data do Vinculo            OPERACIONAL                        NaN
PCDESTAQUE CODUSUARIO   NUMBER(8,0) Código do usuário Cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*