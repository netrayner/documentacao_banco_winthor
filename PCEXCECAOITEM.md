# 📊 Tabela: PCEXCECAOITEM

### Estrutura de Colunas e Restrições

       Tabela         Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOITEM         CODIGO  NUMBER(10,0)     Código sequencial identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOITEM     CODEXCECAO  NUMBER(10,0) Código de identificação do cabeçalho da exceção CHAVE ESTRANGEIRA (FK)         PCEXCECAODOCFISCAL
PCEXCECAOITEM CODTIPOEXCECAO  NUMBER(10,0)                       Código do item da exceção CHAVE ESTRANGEIRA (FK)              PCEXCECAOTIPO
PCEXCECAOITEM          VALOR VARCHAR2(120)                        Valor do item da exceção            OPERACIONAL                        NaN
PCEXCECAOITEM     PRIORIDADE   NUMBER(3,0)                  Prioridade na ordem de exceção            OPERACIONAL                        NaN
PCEXCECAOITEM      DESCRICAO VARCHAR2(250)                    Descrição do item da exceção            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*