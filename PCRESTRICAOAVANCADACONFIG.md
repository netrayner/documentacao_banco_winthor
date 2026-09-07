# 📊 Tabela: PCRESTRICAOAVANCADACONFIG

### Estrutura de Colunas e Restrições

                   Tabela            Coluna   Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAOAVANCADACONFIG         CODCONFIG    NUMBER(4,0)                                                                                 Código da configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCRESTRICAOAVANCADACONFIG            TABELA  VARCHAR2(100)                                                                         Nome da tabela da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG             CAMPO  VARCHAR2(100)                                                                Nome do campo da tabela da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG         TIPOCAMPO   VARCHAR2(20)                                                                Tipo do campo da tabela da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG         NOMELIVRE  VARCHAR2(150)                                            Nome do campo da tabela que será apresentado na rotina 3391            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG     VISIVELFILTRO    VARCHAR2(1)                                        Se a configuração será visível para ser filtrado na rotina 3391            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG    TABELAPESQUISA  VARCHAR2(100)                                    Nome da tabela de pesquisa para buscar a informação da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG     CAMPOPESQUISA  VARCHAR2(100)                           Nome do campo da tabela de pesquisa para buscar a informação da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG DESCRICAOPESQUISA  VARCHAR2(100)              Nome do campo de descrição na tabela de pesquisa para buscar a informação da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG         CODROTULO   VARCHAR2(40)                                            Código do rotulo contendo os tipos de dados da configuração            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG          CONDICAO    VARCHAR2(1)            Se a configuração está disponível na aba "Condição" do cadastro de restrição da rotina 3391            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG      REGRAEXCECAO    VARCHAR2(1) Se a configuração está disponível nas abas "Regra" e "Exceção" do cadastro de restrição da rotina 3391            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG             GRUPO  VARCHAR2(100)                                                                           Nome do grupo de informações            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG     NOMEPARAMETRO  VARCHAR2(100)                                                        Nome do parâmetro de entrada para processamento            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG       CODIGONIVEL    NUMBER(4,0)                                             Código do nível para busca das informações no último nível            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG     TIPOVALIDACAO    VARCHAR2(1)                    Tipo de validação para definir se a mesma é individual ou com os dados consolidados            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG     CHAVEMULTIPLA  VARCHAR2(100)           Chave múltipla para tabelas que tem em sua composição mais de um campo para a chave primária            OPERACIONAL                        NaN
PCRESTRICAOAVANCADACONFIG  CRITERIOPESQUISA VARCHAR2(1000)                                                                                   Critério de Pesquisa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*