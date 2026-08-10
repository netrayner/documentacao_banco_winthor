# 📊 Tabela: PCLISTAPRESENTEC

### Estrutura de Colunas e Restrições

          Tabela                 Coluna   Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLISTAPRESENTEC               NUMLISTA    NUMBER(6,0)                                                               Número de Identificação da Lista    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAPRESENTEC             DTCADASTRO           DATE                                                                      Data do Cadastro da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC             DTVALIDADE           DATE                                                                      Data de Validade da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC             TIPOEVENTO    VARCHAR2(2)                                                                                 Tipo do Evento            OPERACIONAL                        NaN
PCLISTAPRESENTEC             DATAEVENTO           DATE                                                                                 Data do evento            OPERACIONAL                        NaN
PCLISTAPRESENTEC           CIDADEEVENTO  VARCHAR2(100)                                                                               Cidade do Evento            OPERACIONAL                        NaN
PCLISTAPRESENTEC               UFEVENTO    VARCHAR2(2)                                                                                   UF do evento            OPERACIONAL                        NaN
PCLISTAPRESENTEC                 CODCLI    NUMBER(6,0)                                                                   Codigo do Cliente Cadastrado            OPERACIONAL                        NaN
PCLISTAPRESENTEC            NOMETITULAR   VARCHAR2(30)                                                                    Nome do 1º titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC       SOBRENOMETITULAR   VARCHAR2(50)                                                                  Sobrenome do titular da lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC           EMAILTITULAR  VARCHAR2(200)                                                                      Email do titular da lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC             CPFTITULAR   VARCHAR2(11)                                                                        CPF do titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC        ENDERECOTITULAR  VARCHAR2(100)                                                                   Endereço do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          NUMEROTITULAR   VARCHAR2(20)                                                         Número do Endereço do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          COMPLETITULAR   VARCHAR2(50)                                                    Complemento do Endereço do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          CIDADETITULAR  VARCHAR2(100)                                                                     Cidade do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC              UFTITULAR    VARCHAR2(2)                                                                         UF do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC        TELEFONETITULAR   VARCHAR2(20)                                                                   Telefone do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC         CELULARTITULAR   VARCHAR2(20)                                                                    Celular do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC             CEPTITULAR    VARCHAR2(9)                                                                        CEP do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC             NOMECOMPLE   VARCHAR2(30)                                                                    Nome do 2º Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC        SOBRENOMECOMPLE   VARCHAR2(50)                                                               Sobrenome do 2º Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC            EMAILCOMPLE  VARCHAR2(200)                                                                   EMAIL do 2º Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC         NOMEPAITITULAR  VARCHAR2(100)                                                                Nome do Pai do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC         NOMEMAETITULAR  VARCHAR2(100)                                                                Nome da Mãe do Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          NOMEPAICOMPLE  VARCHAR2(100)                                                             Nome do Pai do 2º Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          NOMEMAECOMPLE  VARCHAR2(100)                                                             Nome da Mãe do 2º Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC                 STATUS    VARCHAR2(1)                                                           Situação da Lista (Ativa ou Inativa)            OPERACIONAL                        NaN
PCLISTAPRESENTEC        CODFUNCCADASTRO    NUMBER(6,0)                                                    Codigo do Funcionário que Cadastrou a Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC           DTINATIVACAO           DATE                                                                    Data de Inativação da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC       MOTIVOINATIVACAO VARCHAR2(4000)                                                                  Motivo da Inativação da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC      CODFUNCINATIVACAO    NUMBER(6,0)                                                     Codigo do Funcionário que Inativou a Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC               MENSAGEM           CLOB                                                               Mensagem para o Titular da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC          BAIRROTITULAR   VARCHAR2(50)                                                                              Bairro do Titular            OPERACIONAL                        NaN
PCLISTAPRESENTEC             CODCREDITO    NUMBER(6,0)                                                           Codigo do Crédito Gerado na PCCRECLI            OPERACIONAL                        NaN
PCLISTAPRESENTEC           DTFECHAMENTO           DATE                                                                  Data do Encerramento da Lista            OPERACIONAL                        NaN
PCLISTAPRESENTEC            LOCALEVENTO   VARCHAR2(40)                                                                                Local do evento            OPERACIONAL                        NaN
PCLISTAPRESENTEC ACEITAQTACIMAINFORMADA    VARCHAR2(1) Permite que seja vendido quandidade dos itens acima da quantidade informada pelo dono da lista            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*