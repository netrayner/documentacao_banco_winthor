# 📊 Tabela: PCITEMSOLICITACAOMATERIAL

### Estrutura de Colunas e Restrições

                   Tabela                 Coluna   Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMSOLICITACAOMATERIAL      NUMEROSOLICITACAO   NUMBER(10,0)         Número da Solicitação a que pertence            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL             CODPRODUTO    NUMBER(6,0)                            Código do Produto            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL             QUANTIDADE    NUMBER(6,0)                                   Quantidade            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL           QTDEATENDIDA   NUMBER(14,8)                Quantidade de itens atendidos            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL          QTDEREJEITADA   NUMBER(14,8)               Quantidade de itens rejeitados            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL            QTDECOTACAO   NUMBER(14,8)             Quantidade de itens para cotação            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL     MOTIVOREJEICAOITEM VARCHAR2(2000)                   Motivo da rejeição do item            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL             STATUSITEM    VARCHAR2(2)                               Status do item            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL    DATAATENDIMENTOITEM           DATE                  Data do Atendimento do Item            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL CODFUNCATENDIMENTOITEM    NUMBER(6,0) Código do Funcionário do Atendimento do item            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL             DATAACEITE           DATE         Data aceite dos itens da solicitação            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL     CODFUNCACEITEITENS    NUMBER(6,0)   Código do funcionário do aceite dos itens.            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL              CODFILIAL    VARCHAR2(2)     Código da filial de atendimento do item.            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL               CODCONTA   NUMBER(10,0)                              Codigo da conta            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL               DTCANCEL           DATE                         Data do cancelamento            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL          CODFUNCCANCEL    NUMBER(8,0)    Código do funcionário que cancelou o item            OPERACIONAL                        NaN
PCITEMSOLICITACAOMATERIAL                 RECNUM    NUMBER(8,0)       Número do lançamento do contas a pagar            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*