# 📊 Tabela: PCLAYOUTIMPC

### Estrutura de Colunas e Restrições

      Tabela                    Coluna  Tipo/Tamanho                                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTIMPC                    CODIGO  NUMBER(10,0)                                                            Campo seqüencial para identificar os layouts    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTIMPC               NOMEARQUIVO VARCHAR2(100)                                                 Campo para armazenar o nome do arquivo a ser importado.            OPERACIONAL                        NaN
PCLAYOUTIMPC                 DESCRICAO VARCHAR2(100)                                                             Campo para armazenar a descrição do layout.            OPERACIONAL                        NaN
PCLAYOUTIMPC               TIPOLEITURA   NUMBER(2,0)                  Campo para indicar o tipo de leitura do arquivo: 0-Tipo de Registro e 1-Conteúdo fixo.            OPERACIONAL                        NaN
PCLAYOUTIMPC        IDENTIFICACAOCAMPO   NUMBER(2,0)                 Campo para indicar o tipo da identificação dos campos: 0-Por Separador e 1-Por Tamanho.            OPERACIONAL                        NaN
PCLAYOUTIMPC                 SEPARADOR   VARCHAR2(1)                                         Campo para armazenar o separador a ser utilizado na importação.            OPERACIONAL                        NaN
PCLAYOUTIMPC            TIPOIMPORTACAO   VARCHAR2(2) Campo para indicar o tipo da importação. F-Força de Vendas, R-Rede de cliente e C-Conciliação de cartão            OPERACIONAL                        NaN
PCLAYOUTIMPC TAMANHOIDENTIFICADORSECAO   NUMBER(6,0)                                    Campo para armazenar o tamanho do campo de identificação das seções.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*