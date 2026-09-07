# 📊 Tabela: PCJUSTIFICATIVANOTIFICACOES

### Estrutura de Colunas e Restrições

                     Tabela                Coluna   Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCJUSTIFICATIVANOTIFICACOES             SEQUENCIA   NUMBER(10,0)                  Sequencial de justificativa CHAVE ESTRANGEIRA (FK)             PCNOTIFICACOES
PCJUSTIFICATIVANOTIFICACOES         JUSTIFICATIVA VARCHAR2(2000)                 Justificativa da notificação            OPERACIONAL                        NaN
PCJUSTIFICATIVANOTIFICACOES     NUMEROSOLICITACAO   VARCHAR2(20)            Número da solicitação changepoint            OPERACIONAL                        NaN
PCJUSTIFICATIVANOTIFICACOES CODIGOUSUARIOINCLUSAO    NUMBER(8,0) Código do usuário da inclusão da notificação            OPERACIONAL                        NaN
PCJUSTIFICATIVANOTIFICACOES   CODIGOUSUARIOGESTAO    NUMBER(8,0)      Código do usuário gestor da notificação            OPERACIONAL                        NaN
PCJUSTIFICATIVANOTIFICACOES        MOTIVOREJEICAO VARCHAR2(2000)   Motivo da Rejeição do Recall para a Rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*