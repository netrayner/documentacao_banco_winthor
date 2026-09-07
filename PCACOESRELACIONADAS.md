# 📊 Tabela: PCACOESRELACIONADAS

### Estrutura de Colunas e Restrições

             Tabela             Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCACOESRELACIONADAS CODACAORELACIONADA   NUMBER(4,0)                  Código da ação relacionada    CHAVE PRIMÁRIA (PK)                        NaN
PCACOESRELACIONADAS          CODROTINA   NUMBER(4,0)      Código da rotina que utiliza esta ação    CHAVE PRIMÁRIA (PK)                        NaN
PCACOESRELACIONADAS         TITULOACAO VARCHAR2(100)                              Título do ação            OPERACIONAL                        NaN
PCACOESRELACIONADAS             INDICE   NUMBER(4,0)    Índice para ordenação de criação da ação            OPERACIONAL                        NaN
PCACOESRELACIONADAS              ATIVO       CHAR(1)         Informa se a ação esta ativa ou não            OPERACIONAL                        NaN
PCACOESRELACIONADAS  CODROTINAEXECUTAR   NUMBER(4,0) Código da rotina que será executada na ação            OPERACIONAL                        NaN
PCACOESRELACIONADAS      PARAMEXECUCAO VARCHAR2(100)          Parâmetros para execução da rotina            OPERACIONAL                        NaN
PCACOESRELACIONADAS         DTCADASTRO          DATE                             Data de cadatro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*