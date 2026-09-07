# 📊 Tabela: PCLOGAUTPRECOSERVICO

### Estrutura de Colunas e Restrições

              Tabela             Coluna Tipo/Tamanho                                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGAUTPRECOSERVICO               DATA         DATE                                     No campo será gravado a data de autorização da redução do preço do serviço.            OPERACIONAL                        NaN
PCLOGAUTPRECOSERVICO MATRICULACONECTADO  NUMBER(8,0)                                 No campo será gravado o código do usuário que estará solicitando a autorização.            OPERACIONAL                        NaN
PCLOGAUTPRECOSERVICO MATRICULAPERMISSAO  NUMBER(8,0)                                    No campo será gravado o código do usuário que estará concedendo a permissão.            OPERACIONAL                        NaN
PCLOGAUTPRECOSERVICO              NUMOS  NUMBER(6,0)        No campo será gravado o número da ordem de serviço que foi concedido a autorização para reduzir o preço.            OPERACIONAL                        NaN
PCLOGAUTPRECOSERVICO       NUMOSSERVICO  NUMBER(6,0) No campo será gravado o número do serviço da ordem serviço que foi conedido a autorização para reduzir o preço.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*