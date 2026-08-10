# 📊 Tabela: PCITENSMYFROTA

### Estrutura de Colunas e Restrições

        Tabela              Coluna   Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITENSMYFROTA            CODGRUPO    VARCHAR2(3)                                           Grupo do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA IDINTEGRACAOMYFROTA            RAW                                           Chave da integração.            OPERACIONAL                        NaN
PCITENSMYFROTA              VIAGEM   VARCHAR2(80)                                          Viagem do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA          CODVEICULO    NUMBER(4,0)                                         Veículo do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA                ITEM   VARCHAR2(80)                                            Item do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA      DATALANCAMENTO           DATE                                               Data lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA      DATAVENCIMENTO           DATE                                               Data vencimento.            OPERACIONAL                        NaN
PCITENSMYFROTA           CODFORNEC    NUMBER(6,0)                                        Parceiro do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA          QUANTIDADE   NUMBER(12,4)                                                    Quantidade.            OPERACIONAL                        NaN
PCITENSMYFROTA       VALORUNITARIO   NUMBER(12,4)                                                Valor unitário.            OPERACIONAL                        NaN
PCITENSMYFROTA                ROTA   VARCHAR2(80)                                            Rota do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA           DOCUMENTO   VARCHAR2(40)                                       Documento do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA          OBSERVACAO VARCHAR2(2000)                                      Observação do Lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA           INTEGRADO    VARCHAR2(1)                               Lançamento integrado com PCLANC.            OPERACIONAL                        NaN
PCITENSMYFROTA            CODCONTA   NUMBER(10,0)                       Código da conta gerencial do lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA           CODFILIAL    VARCHAR2(2)                                Código da Filial do lançamento.            OPERACIONAL                        NaN
PCITENSMYFROTA            NUMBANCO   NUMBER(14,2)                    Número do Banco de movimentação financeira.            OPERACIONAL                        NaN
PCITENSMYFROTA            CODMOEDA    VARCHAR2(4)                              Moeda de movimentação financeira.            OPERACIONAL                        NaN
PCITENSMYFROTA              RECNUM    NUMBER(8,0)                 Identificação do lançamento no contas a pagar.            OPERACIONAL                        NaN
PCITENSMYFROTA        CONTASAPAGAR    VARCHAR2(1) Define se o lançamento é de contas a pagar ou de contas pagas.            OPERACIONAL                        NaN
PCITENSMYFROTA             NUMNOTA   NUMBER(10,0)                                         Número da Nota Fiscal.            OPERACIONAL                        NaN
PCITENSMYFROTA         IDSOFITVIEW   VARCHAR2(10)                Indica o código do item da despesa na SofitView            OPERACIONAL                        NaN
PCITENSMYFROTA DTULTALTERSOFITVIEW           DATE                            Data da ultima alteração de despesa            OPERACIONAL                        NaN
PCITENSMYFROTA DTEXCLUSAOSOFITVIEW           DATE                                    Data de exclusão da despesa            OPERACIONAL                        NaN
PCITENSMYFROTA          QTPARCELAS    VARCHAR2(6)                                         QUANTIDADE DE PARCELAS            OPERACIONAL                        NaN
PCITENSMYFROTA        RETEMIMPOSTO    VARCHAR2(1)                       Retenção de imposto referente a serviços            OPERACIONAL                        NaN
PCITENSMYFROTA     GERALIVROFISCAL    VARCHAR2(1)                                             Gerar livro fiscal            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*