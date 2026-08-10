# 📊 Tabela: PCFORNECAVALIAI

### Estrutura de Colunas e Restrições

         Tabela        Coluna  Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECAVALIAI  CODAVALIACAO  NUMBER(10,0)        Indica o código da avaliação.    CHAVE PRIMÁRIA (PK)            PCFORNECAVALIAC
PCFORNECAVALIAI   CODPERGUNTA   NUMBER(6,0)         Indica o código da pergunta.    CHAVE PRIMÁRIA (PK)                PCPERGUNTAS
PCFORNECAVALIAI      RESPOSTA   VARCHAR2(1)                   Indica a resposta.            OPERACIONAL                        NaN
PCFORNECAVALIAI JUSTIFICATIVA VARCHAR2(255) Indica a justificativa da avaliação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*