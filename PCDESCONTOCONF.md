# 📊 Tabela: PCDESCONTOCONF

### Estrutura de Colunas e Restrições

        Tabela                        Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOCONF                    USA_CODCLI  VARCHAR2(1)               Define se irá usar o Código do Cliente            OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_CODEPTO  VARCHAR2(1)          Define se irá usar o Código do Departamento            OPERACIONAL                        NaN
PCDESCONTOCONF                    USA_CODSEC  VARCHAR2(1)                Define ser irá usar o Código da Seção            OPERACIONAL                        NaN
PCDESCONTOCONF              USA_CODCATEGORIA  VARCHAR2(1)            Define se irá usar o Código da Categoria             OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_CODPROD  VARCHAR2(1)              Define ser irá usar o Código do Produto            OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_CODUSUR  VARCHAR2(1)                             Define se irá usar o RCA            OPERACIONAL                        NaN
PCDESCONTOCONF                  USA_CODPLPAG  VARCHAR2(1)    Define se irá usar o Código do Plano de Pagamento            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_CODFORNEC  VARCHAR2(1)            Define se irá usar o Código do Fornecedor            OPERACIONAL                        NaN
PCDESCONTOCONF             USA_CODSUPERVISOR  VARCHAR2(1)            Define se irá usar o Código do Supervisor            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_NUMREGIAO  VARCHAR2(1)                Define se irá usar o Código da Região            OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_CODATIV  VARCHAR2(1)     Define se irá usar o Código do Ramo de Atividade            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_ORIGEMPED  VARCHAR2(1)                Define se irá usar a Origem do Pedido            OPERACIONAL                        NaN
PCDESCONTOCONF                  USA_CODPRACA  VARCHAR2(1)                 Define se irá usar o Código da Praça            OPERACIONAL                        NaN
PCDESCONTOCONF              USA_CODPRODPRINC  VARCHAR2(1)     Define se irá usar o Código do Produto Principal            OPERACIONAL                        NaN
PCDESCONTOCONF               USA_CLASSEVENDA  VARCHAR2(1)                 Define se irá usar a Classe de Venda            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_TIPOCARGA  VARCHAR2(1)     Define se irá usar o Tipo de Entrega Call Center            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_CODPRODCB  VARCHAR2(1)  Define se irá usar o Código do Produto Cesta Básica            OPERACIONAL                        NaN
PCDESCONTOCONF               USA_AREAATUACAO  VARCHAR2(1)           Define se irá usar a Área de Atuação (RCA)            OPERACIONAL                        NaN
PCDESCONTOCONF                 USA_CODFILIAL  VARCHAR2(1)                Define se irá usar o Código da Filial            OPERACIONAL                        NaN
PCDESCONTOCONF              USA_CODGRUPOPROD  VARCHAR2(1)     Define se irá usar o Código do Grupo de Produtos            OPERACIONAL                        NaN
PCDESCONTOCONF                  USA_CODMARCA  VARCHAR2(1)                 Define se irá usar o Código da Marca            OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_CODREDE  VARCHAR2(1)      Define se irá usar o Código de Rede de Clientes            OPERACIONAL                        NaN
PCDESCONTOCONF          USA_CODCONDICAOVENDA  VARCHAR2(1)     Define se irá usar o Código da Condição de Venda            OPERACIONAL                        NaN
PCDESCONTOCONF                    USA_TIPOFJ  VARCHAR2(1)                Define se irá usar o Tipo de Clientes            OPERACIONAL                        NaN
PCDESCONTOCONF              USA_SUBCATEGORIA  VARCHAR2(1)         Define se irá usar o Código da Sub Categoria            OPERACIONAL                        NaN
PCDESCONTOCONF                  USA_QTINIFIM  VARCHAR2(1)         Define se irá usar o Intervalo de Quantidade            OPERACIONAL                        NaN
PCDESCONTOCONF              USA_CODGRUPOREST  VARCHAR2(1)    Define se irá usar o Código do Grupo de Restrição            OPERACIONAL                        NaN
PCDESCONTOCONF             USA_TIPOGRUPOREST  VARCHAR2(1)      Define se irá usar o Tipo de Grupo de Restrição            OPERACIONAL                        NaN
PCDESCONTOCONF           USA_VLRMINIMOMAXIMO  VARCHAR2(1)                  Define se irá usar a Faixa de Valor            OPERACIONAL                        NaN
PCDESCONTOCONF               USA_CODAUXILIAR  VARCHAR2(1)             Define se irá usar o Código da Embalagem            OPERACIONAL                        NaN
PCDESCONTOCONF                USA_CLASSEPROD  VARCHAR2(1)             Define se irá usar a Classe dos Produtos            OPERACIONAL                        NaN
PCDESCONTOCONF               USA_TIPOENTREGA  VARCHAR2(1)                 Define se irá usar o Tipo de Entrega            OPERACIONAL                        NaN
PCDESCONTOCONF USA_APLICADESCSIMPLESNACIONAL  VARCHAR2(1)    Define se irá usar o Desconto P/ Clientes Simples            OPERACIONAL                        NaN
PCDESCONTOCONF       USA_TIPOAPLICDESCONTOCB  VARCHAR2(1)      Define se irá usar o Tipo Aplicação de Desconto            OPERACIONAL                        NaN
PCDESCONTOCONF                    OBR_CODCLI  VARCHAR2(1) Define se é Obrigatório Informar o Código do Cliente            OPERACIONAL                        NaN
PCDESCONTOCONF                   OBR_CODPROD  VARCHAR2(1) Define se é obrigatório informar o Código do Produto            OPERACIONAL                        NaN
PCDESCONTOCONF                 OBR_CODFILIAL  VARCHAR2(1)   Define se é obrigatório informa o Código da Filial            OPERACIONAL                        NaN
PCDESCONTOCONF         USA_QTDAPLICACOESDESC  VARCHAR2(1)       Define se irá usar a Qtde. Máxima por Política            OPERACIONAL                        NaN
PCDESCONTOCONF          USA_QTMINESTPARADESC  VARCHAR2(1)          Define se irá usar a Qtde Mínima de Estoque            OPERACIONAL                        NaN
PCDESCONTOCONF                   USA_NUMORCA  VARCHAR2(1)                Define se irá usar o Número Orçamento            OPERACIONAL                        NaN
PCDESCONTOCONF                     OBR_GRUPO  VARCHAR2(1)           Define se irá utilizar validação por grupo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*