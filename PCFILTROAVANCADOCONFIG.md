# 📊 Tabela: PCFILTROAVANCADOCONFIG

### Estrutura de Colunas e Restrições

                Tabela              Coluna   Tipo/Tamanho                                                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILTROAVANCADOCONFIG           CODCONFIG    NUMBER(4,0)                                                                            Código da configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCFILTROAVANCADOCONFIG               GRUPO  VARCHAR2(100)                                      Nome do grupo de informações (Agrupador dos dados da rotina)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG              TABELA  VARCHAR2(100)                                                     Nome da tabela de configuração (Ex: PCPRODUT)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG               CAMPO  VARCHAR2(100)                                           Nome do campo da tabela de configuração (Ex: CODFORNEC)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG           TIPOCAMPO   VARCHAR2(20)                                              Tipo do campo da tabela de configuração (Ex: NUMBER)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       NOMEPARAMETRO  VARCHAR2(100)                 Nome do parâmetro da tabela de configuração (Quando é chave simples. Ex: CODPROD)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       CHAVEMULTIPLA  VARCHAR2(100)       Chave múltipla da tabela de configuração (Quando tem chave múltipla. Ex: CODPROD;CODFILIAL)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG           NOMELIVRE  VARCHAR2(150)                            Nome livre apresentado nas pesquisas da rotina (Editável pelo usuário)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       VISIVELFILTRO    VARCHAR2(1)                                   Visível no filtro de pesquisa da rotina (Editável pelo usuário)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG     VISIVELCONDICAO    VARCHAR2(1)                               Visível nas condições dos filtros avançados (Editável pelo usuário)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG VISIVELREGRAEXCECAO    VARCHAR2(1)                       Visível nas regras e exceções dos filtros avançados (Editável pelo usuário)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG      TABELAPESQUISA  VARCHAR2(100)                            Nome da tabela de pesquisa para o campo de configuração (Ex: PCFORNEC)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       CAMPOPESQUISA  VARCHAR2(100)                  Nome do campo da tabela de pesquisa para o campo de configuração (Ex: CODFORNEC)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG   DESCRICAOPESQUISA  VARCHAR2(100)    Nome do campo de descrição da coluna de pesquisa para o campo de configuração (Ex: FORNECEDOR)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG    CRITERIOPESQUISA VARCHAR2(1000) Critério de resultado da tabela de pesquisa para o campo de configuração (Ex: DTEXCLUSAO IS NULL)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG      ROTULOPESQUISA   VARCHAR2(40)                   Rótulo de pesquisa para o campo de configuração (Ex: SIMNAO da tabela PCROTULO)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG         CODIGONIVEL    NUMBER(4,0)                                                      Código do nível para o campo de configuração            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       TIPOVALIDACAO    VARCHAR2(1)                         Tipo de validação do campo de configuração (Ex: Individual e Consolidado)            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG          FORMULASQL           CLOB                                              Fórmula em SQL para o cálculo do filtro configurado.            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG       TIPOPARAMETRO  VARCHAR2(100)                                                                      Tipo de dados dos parâmetros            OPERACIONAL                        NaN
PCFILTROAVANCADOCONFIG   DETALHEFORMULASQL           CLOB                                                 Detalhamento da fórmula em SQL (campo FORMULASQL)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*