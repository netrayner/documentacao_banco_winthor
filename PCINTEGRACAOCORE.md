# 📊 Tabela: PCINTEGRACAOCORE

### Estrutura de Colunas e Restrições

          Tabela             Coluna  Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOCORE                 ID  NUMBER(20,0)                                                                       Chave primária da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOCORE          IDWINTHOR  NUMBER(10,0) Id referente ao tipo de integraçao realizado com o winthor. Ex: numtransvenda, codprod, codcli            OPERACIONAL                        NaN
PCINTEGRACAOCORE        DATACRIACAO          DATE                                                                      Data de criação da tabela            OPERACIONAL                        NaN
PCINTEGRACAOCORE      IDROTASERVICO  NUMBER(10,0)                                  Chave estrangeira que faz referência a tabela de rota serviço            OPERACIONAL                        NaN
PCINTEGRACAOCORE     DADOSRECEBIDOS          CLOB                                                      Armazena os dados recebidos da requisição            OPERACIONAL                        NaN
PCINTEGRACAOCORE DADOSTRANSFORMADOS          CLOB                                                                Armazena os dados transformados            OPERACIONAL                        NaN
PCINTEGRACAOCORE   DADOSDEPENDENTES          CLOB                                                                  Armazena os dados dependentes            OPERACIONAL                        NaN
PCINTEGRACAOCORE          IDEXTERNO VARCHAR2(100)                                                         Armazena os id externo das integrações            OPERACIONAL                        NaN
PCINTEGRACAOCORE         TENTATIVAS   NUMBER(5,0)                                                           Quantidade de tentativas de execução            OPERACIONAL                        NaN
PCINTEGRACAOCORE      TIPODOCUMENTO  VARCHAR2(40)                                                                   Tipo documento da integração            OPERACIONAL                        NaN
PCINTEGRACAOCORE         OBSERVACAO          CLOB                          Armazena os dados de observação tanto para sucesso, quanto para falha            OPERACIONAL                        NaN
PCINTEGRACAOCORE       IDREQUISICAO VARCHAR2(100)                                                                Id requisição referente ao lote            OPERACIONAL                        NaN
PCINTEGRACAOCORE    DATASINCRONISMO          DATE                                                               Armazenada a data de sincronismo            OPERACIONAL                        NaN
PCINTEGRACAOCORE  IDPROCESSOWINTHOR   NUMBER(1,1)                                                              Armazena o id do processo winthor            OPERACIONAL                        NaN
PCINTEGRACAOCORE    IDDADOSRECEBIDO  NUMBER(20,0)                               Chave extrangeira que faz referência a tabela de dados recebidos CHAVE ESTRANGEIRA (FK) PCINTEGRACAODADOSRECEBIDOS
PCINTEGRACAOCORE             STATUS   VARCHAR2(2)                       Armazena o status da integração. Ex: 1 - recebido, 2- sucesso e 3 - erro            OPERACIONAL                        NaN
PCINTEGRACAOCORE          IDINTERNO VARCHAR2(100)                                                               Armazena o id interno do winthor            OPERACIONAL                        NaN
PCINTEGRACAOCORE         DTULTALTER          DATE                                                            Armazena a data de última alteração            OPERACIONAL                        NaN
PCINTEGRACAOCORE PAYLOADCONFIRMACAO          CLOB                                                              Armazena o payload de confirmação            OPERACIONAL                        NaN
PCINTEGRACAOCORE  IDREQUISICAOENVIO VARCHAR2(100)                                     Armazena o ID de requisição para envio (referente ao lote)            OPERACIONAL                        NaN
PCINTEGRACAOCORE IDROTASERVICOENVIO  NUMBER(10,0)                                                                     Id rota serviço para envio            OPERACIONAL                        NaN
PCINTEGRACAOCORE          VARIAVEIS          CLOB               Coluna destinada ao armazenamento das variáveis utilizadas na execução do fluxo;            OPERACIONAL                        NaN
PCINTEGRACAOCORE        REPROCESSAR   VARCHAR2(1)                                           Indica se o registro está sendo reprocessado ou não;            OPERACIONAL                        NaN
PCINTEGRACAOCORE            IDFLUXO  NUMBER(10,0)                                                                Coluna para referenciar o fluxo            OPERACIONAL                        NaN
PCINTEGRACAOCORE   CODEMPRESAFILIAL VARCHAR2(255)                                                          Código da empresa filial do registro.            OPERACIONAL                        NaN
PCINTEGRACAOCORE     IDCARGAINICIAL  NUMBER(10,0)                                                                            Id da carga inicial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*