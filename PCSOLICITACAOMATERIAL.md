# 📊 Tabela: PCSOLICITACAOMATERIAL

### Estrutura de Colunas e Restrições

               Tabela                  Coluna   Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSOLICITACAOMATERIAL       NUMEROSOLICITACAO   NUMBER(10,0)                            Número da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL             DATACRIACAO           DATE                   Data da Criação da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL           DATAAPROVACAO           DATE                 Data da Aprovação da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL            DATAREJEICAO           DATE                  Data da Rejeição da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL                  STATUS    VARCHAR2(1)                            Status da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL      CODFUNCSOLICITANTE    NUMBER(8,0)                          Funcionário Solicitante            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL      CODFUNCBENEFICIADO    NUMBER(8,0)                          Funcionário Beneficiado            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL    CODFUNCAPROVAREJEITA    NUMBER(8,0)                Funcionário Aprovação ou Rejeição            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL                  MOTIVO VARCHAR2(2000)                            Motivo da Solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL                DTCANCEL           DATE                             Data do cancelamento            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL           CODFUNCCANCEL    NUMBER(8,0) Código do funcionário que cancelou a solicitação            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL           DATADEVOLUCAO           DATE                                Data da devolução            OPERACIONAL                        NaN
PCSOLICITACAOMATERIAL NUMEROSOLICITACAOORIGEM   NUMBER(10,0)                  Número da solicitação de origem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*