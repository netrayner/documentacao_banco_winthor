# 📊 Tabela: PCGMPARAMMETA

### Estrutura de Colunas e Restrições

       Tabela                   Coluna  Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPARAMMETA                   CODIGO  NUMBER(10,0)                                                                       Código da parametrização    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPARAMMETA                DESCRICAO VARCHAR2(255)                                                                    Descrição da parametrização            OPERACIONAL                        NaN
PCGMPARAMMETA                     TIPO   VARCHAR2(3)                                                             Tipo da parametrização: Sec ou Pri            OPERACIONAL                        NaN
PCGMPARAMMETA                CODPERFIL  NUMBER(10,0)                                                             Código do perfil da parametrização CHAVE ESTRANGEIRA (FK)                 PCGMPERFIL
PCGMPARAMMETA              ABRANGENCIA   VARCHAR2(3)                                                    Abrangencia das entidades da parametrização            OPERACIONAL                        NaN
PCGMPARAMMETA               CODPERIODO  NUMBER(10,0)                                                  Código do periodo utilizado na parametrização CHAVE ESTRANGEIRA (FK)                PCGMPERIODO
PCGMPARAMMETA                 SITUACAO   VARCHAR2(1)                                                                     Situação da parametrização            OPERACIONAL                        NaN
PCGMPARAMMETA             METEDITCOLAB   VARCHAR2(1)                                            Se meta poderá ser editada pelo próprio colaborador            OPERACIONAL                        NaN
PCGMPARAMMETA          METAPROVSUPIMED   VARCHAR2(1)                              Se meta poderá ser aprovada pelo superior imediato do colaborador            OPERACIONAL                        NaN
PCGMPARAMMETA      METAPROVMAISINSTSUP   VARCHAR2(1)                                    Se meta poderá ser aprovada por mais uma instância superior            OPERACIONAL                        NaN
PCGMPARAMMETA         VERIFICAITEMNOVO   VARCHAR2(1)                      Se irá verificar a existencia de itens novos para serem incluidos na meta            OPERACIONAL                        NaN
PCGMPARAMMETA               CODUSUARIO   NUMBER(8,0)                                                                Matricula do usuário do sistema            OPERACIONAL                        NaN
PCGMPARAMMETA             DATAEXCLUSAO          DATE                                                                               Data da exclusão            OPERACIONAL                        NaN
PCGMPARAMMETA                CODFILIAL   VARCHAR2(2)                                                             Código da filial da parametrização            OPERACIONAL                        NaN
PCGMPARAMMETA     CODPARAMMETABASEDESD  NUMBER(10,0) Código da parametrização utilizada como base para a criação de outra, por meio de agrupamento.            OPERACIONAL                        NaN
PCGMPARAMMETA CODPARAMMETABASEAGRUPADO  NUMBER(10,0) Código da parametrização utilizada como base para a criação de outra, por meio de agrupamento.            OPERACIONAL                        NaN
PCGMPARAMMETA    CODPARAMMETAREPLICADO  NUMBER(10,0)        Código da parametrização utilizada como base para a criação de outra, apenas replicando            OPERACIONAL                        NaN
PCGMPARAMMETA    USABASEDADOSHISTORICO   VARCHAR2(2)                                      Se meta utiliza dados históricos para o valor do previsto            OPERACIONAL                        NaN
PCGMPARAMMETA     ORIGEMDADOSHISTORICO   VARCHAR2(2)                                                        De qual perfil utiliza origem dos dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*