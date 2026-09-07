# 📊 Tabela: PCOPERADORACARTAO

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho                                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOPERADORACARTAO              CODIGO   VARCHAR2(6)                                                     Campo para armazenar o código da operadora de cartão.    CHAVE PRIMÁRIA (PK)                        NaN
PCOPERADORACARTAO           OPERADORA VARCHAR2(100)                                                       Campo para armazenar o nome da operadora de cartão.            OPERACIONAL                        NaN
PCOPERADORACARTAO            PERCDESC   NUMBER(4,2) Campo para armazenar o percentual de desconto referente à comissão da operadora e o aluguel da maquineta.            OPERACIONAL                        NaN
PCOPERADORACARTAO        CODLAYOUTIMP  NUMBER(10,0)     Campo para armazenar o código do layout a ser utilizado para importação de arquivos para conciliação.            OPERACIONAL                        NaN
PCOPERADORACARTAO              CODCLI   NUMBER(6,0)                                                                               Indica o código do cliente.            OPERACIONAL                        NaN
PCOPERADORACARTAO     CODOPERSITEFWEB   VARCHAR2(6)                                                                    Indica o código da operadora SITEFWEB.            OPERACIONAL                        NaN
PCOPERADORACARTAO         CODBANDEIRA   NUMBER(6,0)                                                                                       Codigo da Bandeira.            OPERACIONAL                        NaN
PCOPERADORACARTAO        NOMEBANDEIRA  VARCHAR2(30)                                                                                         Nome da Bandeira.            OPERACIONAL                        NaN
PCOPERADORACARTAO           SUBCODIGO   VARCHAR2(6)                                                                                   Sub Código da Operadora            OPERACIONAL                        NaN
PCOPERADORACARTAO CODESTABADIQUIRENTE  VARCHAR2(25)                                                                        Codigo estavelacimento adiquerinte            OPERACIONAL                        NaN
PCOPERADORACARTAO        CODADMCARTAO   VARCHAR2(3)                                                                              Código administradora cartão            OPERACIONAL                        NaN
PCOPERADORACARTAO          DTULTALTER          DATE                                                                      Data da última alteração do registro            OPERACIONAL                        NaN
PCOPERADORACARTAO          DTCADASTRO          DATE                                                                               Data de criação do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*