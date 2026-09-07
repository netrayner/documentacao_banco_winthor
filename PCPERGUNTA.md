# 📊 Tabela: PCPERGUNTA

### Estrutura de Colunas e Restrições

    Tabela       Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERGUNTA  CODPESQUISA   NUMBER(8,0)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPERGUNTA  CODPERGUNTA   NUMBER(8,0)                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPERGUNTA     PERGUNTA VARCHAR2(200)                          NaN            OPERACIONAL                        NaN
PCPERGUNTA TIPORESPOSTA   VARCHAR2(1)                          NaN            OPERACIONAL                        NaN
PCPERGUNTA    ENCADEADA   VARCHAR2(1)                          NaN            OPERACIONAL                        NaN
PCPERGUNTA       MODULO   NUMBER(3,0) Indica o modulo da pergunta.            OPERACIONAL                        NaN
PCPERGUNTA   CODSERVICO   NUMBER(6,0)  Indica o código do serviço.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*