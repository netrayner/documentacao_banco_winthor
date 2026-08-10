# 📊 Tabela: PCTREINAMENTO

### Estrutura de Colunas e Restrições

       Tabela     Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTREINAMENTO  DESCRICAO VARCHAR2(100)      Descrição do Treinamento            OPERACIONAL                        NaN
PCTREINAMENTO      ORDEM   NUMBER(4,0)          Ordem do Treinamento            OPERACIONAL                        NaN
PCTREINAMENTO  CODMODULO   NUMBER(4,0)  Código do Modulo Treinamento CHAVE ESTRANGEIRA (FK)           PCMODTREINAMENTO
PCTREINAMENTO   ENDERECO VARCHAR2(500) Endereço(link) do treinamento            OPERACIONAL                        NaN
PCTREINAMENTO DTINCLUSAO          DATE              Data de Inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*