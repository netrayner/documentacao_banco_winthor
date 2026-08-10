# 📊 Tabela: PCCONFIGPRECIFICMED

### Estrutura de Colunas e Restrições

             Tabela                        Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGPRECIFICMED                     CODFILIAL   VARCHAR2(2)                                     Código    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFIGPRECIFICMED    APRESENTARDESC2DESCREPASSE   VARCHAR2(1)                Apresentar desconto repasse            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED         DTFINATUVLVENDAMESMED          DATE             Data final de ultima venda mês            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED         DTINIATUVLVENDAMESMED   VARCHAR2(1)           Data inicial de ultima venda mês            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED      IMPEDIRPRECOACIMAFABRICA   VARCHAR2(1)                   IMPEDIRPRECOACIMAFABRICA            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED LISTAPROMOCOESPRECOMEDIOVENDA VARCHAR2(250)                         Lista de promoções            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED             MARGEMPELABASERCA   VARCHAR2(1)                                     Margem            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED          MODOGRAVACAORASCUNHO   VARCHAR2(1)                              Modo rascunho            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED           NUMCASASDECDESCONTO   NUMBER(6,0)                   Numero de casas desconto            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED       OPCAOPADRAOTIPOPOLITICA   VARCHAR2(1)                              Tipo politica            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED         OPCAOPRECOMINIMOVENDA   VARCHAR2(1)               Opção preço mínimo de vendas            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED            OPCAOSTCUSTOULTENT   VARCHAR2(1)        Opção de St custo da ultima entrada            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED     PERCFINALCORRENTABILIDADE   NUMBER(5,2)             Percentual final contabilidade            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED   PERCINICIALCORRENTABILIDADE   NUMBER(5,2)           Percentual inicial contabilidade            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED                      PERCIRRF   NUMBER(5,2)                            Percentual IRRF            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED                    PRAZOMEDIO   NUMBER(3,0)                                Prazo médio            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED           PRECOFABRICAINICIAL   VARCHAR2(1)                      Preço fábrica inicial            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED     QTDEDIASVENCIMENTOPROXIMO   NUMBER(9,0)              Quantidade dias próximo vecto            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED  REGRATUALIZARPRECOPELAMARGEM   VARCHAR2(1)                  Utiliza preço pela margem            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED                  TIPOCOMISSAO   VARCHAR2(2)                           Tipo de comissão            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED             TIPORENTABILIDADE   VARCHAR2(1)                      Tipo de rentabilidade            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED       USARPROMOUNICAFAIXAQTDE   VARCHAR2(1)                        Usar promoção única            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED       USARUTILIZAPRECOFABRICA   VARCHAR2(1)                      Utiliza preço fábrica            OPERACIONAL                        NaN
PCCONFIGPRECIFICMED        MANTERCOMISSAOPROMOCAO   VARCHAR2(1) Define se irá Manter Comissões da Promoção            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*