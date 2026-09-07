# 📊 Tabela: PCPERGUNTAS

### Estrutura de Colunas e Restrições

     Tabela       Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERGUNTAS  CODPERGUNTA   NUMBER(6,0)       Indica o código da pergunta.    CHAVE PRIMÁRIA (PK)                        NaN
PCPERGUNTAS    DESCRICAO VARCHAR2(150)    Indica a descrição da pergunta.            OPERACIONAL                        NaN
PCPERGUNTAS         TIPO   NUMBER(1,0)         Indica o tipo da pergunta.            OPERACIONAL                        NaN
PCPERGUNTAS QUALIFICACAO   VARCHAR2(1) Indica a pergunta de qualificação.            OPERACIONAL                        NaN
PCPERGUNTAS    AVALIACAO   VARCHAR2(1)    Indica a pergunta de avaliação.            OPERACIONAL                        NaN
PCPERGUNTAS        ATIVO   VARCHAR2(1)      Indica a pergunta esta ativa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*