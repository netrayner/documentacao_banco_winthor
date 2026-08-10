# 📊 Tabela: PCORCAVENDAIDEVOL

### Estrutura de Colunas e Restrições

           Tabela              Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORCAVENDAIDEVOL             NUMORCA  NUMBER(10,0)                    Número de orçamento            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL             CODPROD   NUMBER(6,0)                      Código do produto            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL              NUMSEQ  NUMBER(20,0)                      Número sequêncial            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL              PVENDA  NUMBER(19,6)                         Preço de Venda            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL             PTABELA  NUMBER(19,6)                        Preço de Tabela            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL                  QT  NUMBER(20,6)                   Quantidade Devolvida            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL         CODAUXILIAR  NUMBER(20,0)                          Código Barras            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL               CODST   NUMBER(4,0)                           Código do ST            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL            NUMFICHA  NUMBER(10,0)                        Número da Ficha            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL           DATADEVOL          DATE                      Data da Devolução            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL   CODSUPERVLIBDEVOL   NUMBER(8,0)           Cód.Supervisor que autorizou            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL     CODUSUARIODEVOL   NUMBER(8,0)                  Cód.Usuário Devolução            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL    CODUSUARIOPEDIDO   NUMBER(8,0)                     Cód.Usuário Pedido            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL     NUMSEQIMPRESSAO  NUMBER(20,0)            Núm.Sequencial de Impressão            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL              CODIMP   NUMBER(6,0)                         Cód.Impressora            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL  IMPRIMERESTAURANTE   VARCHAR2(1)              Deve Imprimir Restaurante            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL IMPRESSORESTAURANTE   VARCHAR2(1)         Já foi impresso no restaurante            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL           HISTORICO VARCHAR2(200)                 Histórico da devolução            OPERACIONAL                        NaN
PCORCAVENDAIDEVOL    DTENVIOSERVCARGA          DATE Data de envio para o servidor de carga            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*