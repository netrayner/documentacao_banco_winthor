# 📊 Tabela: PCMETAVAREJO

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAVAREJO          CODIGO  NUMBER(8,0)                                         CÓDIGO DA META    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAVAREJO       CODFILIAL  VARCHAR2(2)                                       CÓDIGO DA FILIAL            OPERACIONAL                        NaN
PCMETAVAREJO        TIPOMETA  VARCHAR2(2)                                           TIPO DA META            OPERACIONAL                        NaN
PCMETAVAREJO        DTINICIO         DATE                                   DATA INICIAL DA META            OPERACIONAL                        NaN
PCMETAVAREJO           DTFIM         DATE                                     DATA FINAL DA META            OPERACIONAL                        NaN
PCMETAVAREJO          COLUNA VARCHAR2(32)                            COLUNA DE ALTERAÇÃO DA META            OPERACIONAL                        NaN
PCMETAVAREJO        FAIXAINI NUMBER(12,4)                         FAIXA DE VALOR INICIAL DA META            OPERACIONAL                        NaN
PCMETAVAREJO        FAIXAFIM NUMBER(12,4)                           FAIXA DE VALOR FINAL DA META            OPERACIONAL                        NaN
PCMETAVAREJO        QTPONTOS  NUMBER(8,2)                           QUANTIDADE DE PONTOS DA META            OPERACIONAL                        NaN
PCMETAVAREJO      TIPOPREMIO  VARCHAR2(2)                                 TIPO DO PREMIO DA META            OPERACIONAL                        NaN
PCMETAVAREJO         CODIGO2  NUMBER(8,0)                              CÓDIGO SECUNDARIO DA META            OPERACIONAL                        NaN
PCMETAVAREJO CODFUNCCADASTRO  NUMBER(8,0)                       CÓDIGO FUNCIONÁRIO QUE CADASTROU            OPERACIONAL                        NaN
PCMETAVAREJO      DTCADASTRO         DATE                                  DATA CADASTRO DA META            OPERACIONAL                        NaN
PCMETAVAREJO   CODFUNCULTALT  NUMBER(8,0)                         CÓDIGO FUNCIONÁRIO QUE ALTEROU            OPERACIONAL                        NaN
PCMETAVAREJO        DTULTALT         DATE                               DATA DA ULTIMA ALTERAÇÃO            OPERACIONAL                        NaN
PCMETAVAREJO CODFUNCEXCLUSAO  NUMBER(8,0)                      CÓDIGO DO FUNCIONÁRIO DA EXCLUSÃO            OPERACIONAL                        NaN
PCMETAVAREJO      DTEXCLUSAO         DATE                                       DATA DA EXCLUSÃO            OPERACIONAL                        NaN
PCMETAVAREJO         CODIGO3  NUMBER(8,0)                                           Código Seçao            OPERACIONAL                        NaN
PCMETAVAREJO         CODIGO4  NUMBER(8,0)                                       Código Categoria            OPERACIONAL                        NaN
PCMETAVAREJO         CODIGO5  NUMBER(8,0)                                   Código Sub Categoria            OPERACIONAL                        NaN
PCMETAVAREJO         CODIGO6  NUMBER(8,0)                                 Código da Subcategoria            OPERACIONAL                        NaN
PCMETAVAREJO         CODEPTO  NUMBER(8,0)                                    Código departamento            OPERACIONAL                        NaN
PCMETAVAREJO        CODSECAO  NUMBER(8,0)                                           Código seção            OPERACIONAL                        NaN
PCMETAVAREJO    CODCATEGORIA  NUMBER(8,0)                                       Código categoria            OPERACIONAL                        NaN
PCMETAVAREJO CODSUBCATEGORIA  NUMBER(8,0)                                    Código subcategoria            OPERACIONAL                        NaN
PCMETAVAREJO       TPPERIODO  VARCHAR2(2)                       Tipo de periodo base selecionado            OPERACIONAL                        NaN
PCMETAVAREJO          DTBASE         DATE                                    Data base informada            OPERACIONAL                        NaN
PCMETAVAREJO         MESORIG  NUMBER(2,0)                                     Mês base informado            OPERACIONAL                        NaN
PCMETAVAREJO         ANOORIG  NUMBER(4,0)                                     Ano base informado            OPERACIONAL                        NaN
PCMETAVAREJO          DTMETA         DATE                             Data planejada para a meta            OPERACIONAL                        NaN
PCMETAVAREJO         MESMETA  NUMBER(2,0)                              Mês planejado para a meta            OPERACIONAL                        NaN
PCMETAVAREJO         ANOMETA  NUMBER(4,0)                              Ano Planejado para a meta            OPERACIONAL                        NaN
PCMETAVAREJO   PERCACRESCIMO NUMBER(12,4) Percentual de acréscimo informado para cálcular a meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*