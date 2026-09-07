# 📊 Tabela: PCINTEGRACAOVARIAVEIS

### Estrutura de Colunas e Restrições

               Tabela          Coluna  Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOVARIAVEIS              ID  NUMBER(10,0)                                                  Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOVARIAVEIS           CHAVE  VARCHAR2(40)               Chave cadastrada nos layouts de comunicação e transformação            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS       TIPOCHAVE  VARCHAR2(20)    Armazena a parte do layout que a chave foi criada. Ex: (BODY, HEADER)             OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS       TIPOVALOR  VARCHAR2(20) Armazena o tipo de valor referente a chave. EX: (string, integer, select)            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS   IDROTASERVICO  NUMBER(10,0)                           Chave extrangeira para a tabela de rota serviço CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAOVARIAVEIS      DTULTALTER          DATE                                                  Data de última alteração            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS     CODEMPALTER  VARCHAR2(40)                                                      Código emp alteração            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS           VALOR          CLOB                                        Armazena o valor referente a chave            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS    PARAMSISTEMA   VARCHAR2(1)              N para Parâmetros de Usuário e S para Parâmetros de Sistema.            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS   VISIVELWIZARD   VARCHAR2(1)                 Informa se parametro esta visivel no Wizard. ex: S ou N\t            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS ORDENACAOWIZARD  NUMBER(10,0)                                              Ordem do Parametro no Wizard            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS  DESCRICAOPARAM VARCHAR2(150)                                              Breve descricao do Parametro            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEIS IDEMPRESAFILIAL  NUMBER(10,0)                                         Id da empresa filial da variável.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*