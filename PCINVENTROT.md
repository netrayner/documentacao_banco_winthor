# 📊 Tabela: PCINVENTROT

### Estrutura de Colunas e Restrições

     Tabela                         Coluna  Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTROT                      NUMINVENT   NUMBER(8,0)                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTROT                           DATA          DATE                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                      CODFILIAL   VARCHAR2(2)                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTROT                        CODPROD   NUMBER(6,0)                                                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTROT                            QT1  NUMBER(22,8)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                            QT2  NUMBER(22,8)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                            QT3  NUMBER(22,8)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                       QTESTGER  NUMBER(22,8)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                      DATACONT1          DATE                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                      DATACONT2          DATE                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                      DATACONT3          DATE                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT1CX  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT2CX  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT3CX  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT1CT  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT2CT  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT3CT  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT1UN  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT2UN  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT3UN  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT1LJ  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT2LJ  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                          QT3LJ  NUMBER(16,3)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT                         NUMSEQ  NUMBER(10,0)                                                                                  NaN            OPERACIONAL                        NaN
PCINVENTROT             CODFUNCATUALIZACAO   NUMBER(8,0)                                                Código do funcionario da atualização.            OPERACIONAL                        NaN
PCINVENTROT                  DTATUALIZACAO          DATE                                                                 Data da atualização.            OPERACIONAL                        NaN
PCINVENTROT                CODFUNCMONTAGEM   NUMBER(8,0)                                    Indica o código do funcionário montador do bônus.            OPERACIONAL                        NaN
PCINVENTROT                       CODLOCAL  VARCHAR2(20)                                                                     Código do local.    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTROT                      QTAVARIA1  NUMBER(18,4)                                                 Quantidade avaria primeira contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTAVARIA2  NUMBER(18,4)                                                  Quantidade avaria segunda contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTAVARIA3  NUMBER(18,4)                                                 Quantidade avaria terceira contagem.            OPERACIONAL                        NaN
PCINVENTROT                   INVENTAVARIA   VARCHAR2(1)                                                                 Inventariar avarias.            OPERACIONAL                        NaN
PCINVENTROT               AVARIAATUALIZADA   VARCHAR2(1)                                                                 Avarias atualizadas.            OPERACIONAL                        NaN
PCINVENTROT                         QTCONT  NUMBER(22,8)                                                         Estoque Contábil do produto.            OPERACIONAL                        NaN
PCINVENTROT                          CUSTO  NUMBER(18,6)                                                                    Custo do produto.            OPERACIONAL                        NaN
PCINVENTROT                   DATAFECCONT1          DATE                                                                 Data de conferência.            OPERACIONAL                        NaN
PCINVENTROT                   DATAFECCONT2          DATE                                                                 Data de conferência.            OPERACIONAL                        NaN
PCINVENTROT                   DATAFECCONT3          DATE                                                                 Data de conferência.            OPERACIONAL                        NaN
PCINVENTROT                    CODFUNCFEC1   NUMBER(8,0)                                                               Código do funcionário.            OPERACIONAL                        NaN
PCINVENTROT                    CODFUNCFEC2   NUMBER(8,0)                                                               Código do funcionário.            OPERACIONAL                        NaN
PCINVENTROT                    CODFUNCFEC3   NUMBER(8,0)                                                               Código do funcionário.            OPERACIONAL                        NaN
PCINVENTROT                          QTEST  NUMBER(22,8)                                                          Estoque Contábil do produto            OPERACIONAL                        NaN
PCINVENTROT           QTUTILIZAATUALIZACAO  NUMBER(22,8)                                      Quantidade utilizada na atualização do estoque.            OPERACIONAL                        NaN
PCINVENTROT                       DTCANCEL          DATE                                                                 Data de cancelamento            OPERACIONAL                        NaN
PCINVENTROT                  CODFUNCCANCEL   NUMBER(8,0)                                                                 Usuário cancelamento            OPERACIONAL                        NaN
PCINVENTROT        INVENTARIASOMENTEAVARIA   VARCHAR2(1)                                                            Inventaria somente avaria            OPERACIONAL                        NaN
PCINVENTROT                   CODFUNCCONT1   NUMBER(8,0)                                           Código do primeiro funcionário da contagem            OPERACIONAL                        NaN
PCINVENTROT                   CODFUNCCONT2   NUMBER(8,0)                                            Código do segundo funcionário da contagem            OPERACIONAL                        NaN
PCINVENTROT                   CODFUNCCONT3   NUMBER(8,0)                                           Código do terceiro funcionário da contagem            OPERACIONAL                        NaN
PCINVENTROT          DTATUALIZACAONUMSERIE          DATE                                           Data de atualização inventario num. Serie.            OPERACIONAL                        NaN
PCINVENTROT                           NOME  VARCHAR2(50)                                                                   Nome do inventário            OPERACIONAL                        NaN
PCINVENTROT                ALTEROUCONTAGEM   VARCHAR2(1)                       Flag para validar se houve alteração na contagem do inventário            OPERACIONAL                        NaN
PCINVENTROT                      QTINDENIZ  NUMBER(20,6)                                         QTINDENIZ antes da atualização do inventario            OPERACIONAL                        NaN
PCINVENTROT                 GERARNFENTRADA   VARCHAR2(1)                          Indica se foi gerada NF de entrada do inventário pela 1188.            OPERACIONAL                        NaN
PCINVENTROT                      QTESTGER1  NUMBER(22,8)                              Quantidade de estoque gerencial no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTESTGER2  NUMBER(22,8)                              Quantidade de estoque gerencial no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTESTGER3  NUMBER(22,8)                              Quantidade de estoque gerencial no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTRESERV1  NUMBER(22,8)                              Quantidade de estoque reservado no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTRESERV2  NUMBER(22,8)                              Quantidade de estoque reservado no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                      QTRESERV3  NUMBER(22,8)                              Quantidade de estoque reservado no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                     QTINDENIZ1  NUMBER(22,8)                              Quantidade de estoque em avaria no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                     QTINDENIZ2  NUMBER(22,8)                              Quantidade de estoque em avaria no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT                     QTINDENIZ3  NUMBER(22,8)                              Quantidade de estoque em avaria no momento da contagem.            OPERACIONAL                        NaN
PCINVENTROT        ZERARESTOQUESEMCONTAGEM   VARCHAR2(1)                                              Zerar estoque dos produtos sem contagem            OPERACIONAL                        NaN
PCINVENTROT                       TIPOCONT   VARCHAR2(1)                                                       Tipo de contagem no inventário            OPERACIONAL                        NaN
PCINVENTROT                       DEPOSITO   VARCHAR2(1)                                Identifica se o registro de inventário e por depósito            OPERACIONAL                        NaN
PCINVENTROT                  QTESTDEPOSITO  NUMBER(22,8)                           Quantidade atual do estoque quando se iniciou o inventário            OPERACIONAL                        NaN
PCINVENTROT             QTESTDEPOSITOSALDO  NUMBER(22,8)                                     Quantidade total de estoque dos demais depósitos            OPERACIONAL                        NaN
PCINVENTROT  CONSIDERARSOMENTEPRIMEIRACONT   VARCHAR2(1)                          Flag para validar se considera somente a primeira contagem.            OPERACIONAL                        NaN
PCINVENTROT ATUALIZARINVENTARIOCOMAUSENCIA   VARCHAR2(1)       Flag para verificar se atualiza o inventário mesmo sem digitar todos os itens.            OPERACIONAL                        NaN
PCINVENTROT ZERARESTOQUESEMCONTATUALIZACAO   VARCHAR2(1) Flag para verificar se permite zerar estoque na ausência de contagem na atualização.            OPERACIONAL                        NaN
PCINVENTROT            EDITARCENTRODECUSTO   VARCHAR2(1)                               Flag para verificar se permite editar centro de custo.            OPERACIONAL                        NaN
PCINVENTROT            HISTORICOLANCAMENTO VARCHAR2(200)                                                            Histórico de lançamentos.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*