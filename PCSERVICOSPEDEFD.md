# 📊 Tabela: PCSERVICOSPEDEFD

### Estrutura de Colunas e Restrições

          Tabela                        Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOSPEDEFD                    CODSERVICO  NUMBER(8,0)                                Código do serviço que faz vinculo com a PCLANC            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                 CODCONSTCIVIL  NUMBER(2,0)                             Prestação de Serviços em obra de Construção Civil            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                CODTIPOSERVICO  VARCHAR2(9) CLASSIFICAÇÃO DE SERVIÇOS PRESTADOS MEDIANTE CESSÃO DE MÃO DE OBRA/EMPREITADA            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                       SERIENF  VARCHAR2(5)                                               Série na nota fiscal de serviço            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                       CODCNAE  VARCHAR2(8)                        Código do CNAE do serviço sujeito a incidência da CPRB            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                  VALORBRUTONF NUMBER(14,2)                                                    Valor bruto da nota fiscal            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                 VALORMATERIAL NUMBER(14,2)                                             Valor dos Materiais e Equipamento            OPERACIONAL                        NaN
PCSERVICOSPEDEFD              VALORALIMENTACAO NUMBER(14,2)                                                          Valor da Alimentação            OPERACIONAL                        NaN
PCSERVICOSPEDEFD               VALORTRANSPORTE NUMBER(14,2)                                                           Valor do Transporte            OPERACIONAL                        NaN
PCSERVICOSPEDEFD             VALORBASERETENCAO NUMBER(14,2)                                                        Valor base da Retenção            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                  PERCRETENCAO NUMBER(14,2)                                                        Percentual da Retenção            OPERACIONAL                        NaN
PCSERVICOSPEDEFD             VALORRETANTESDEDU NUMBER(14,2)               Valor da Retenção antes da Dedução dos Valores da Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD          VALORRETEMPSUBCONTRA NUMBER(14,2)                                    Valor da Retenção da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                   VALORRETIDO NUMBER(14,2)                                                                  Valor Retido            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                VALORADICIONAL NUMBER(14,2)                                                               Valor Adicional            OPERACIONAL                        NaN
PCSERVICOSPEDEFD           VALORSERVAPOS15ANOS NUMBER(14,2)                               Valor do serviço aposentadoria especial 15 anos            OPERACIONAL                        NaN
PCSERVICOSPEDEFD           VALORSERVAPOS20ANOS NUMBER(14,2)                               Valor do serviço aposentadoria especial 20 anos            OPERACIONAL                        NaN
PCSERVICOSPEDEFD           VALORSERVAPOS25ANOS NUMBER(14,2)                               Valor do serviço aposentadoria especial 25 anos            OPERACIONAL                        NaN
PCSERVICOSPEDEFD    VALORRETNAOEFETCONTRATANTE NUMBER(14,2)                 Valor da Retenção que deixou de ser efetuada pelo contratante            OPERACIONAL                        NaN
PCSERVICOSPEDEFD VALORRETADINAOEFETCONTRATANTE NUMBER(14,2)       Valor da Retenção Adicional que deixou de ser efetuada pelo contratante            OPERACIONAL                        NaN
PCSERVICOSPEDEFD         NUMINSCSUBCONTRATANTE VARCHAR2(30)                                         Número da inscrição do Subcontratante            OPERACIONAL                        NaN
PCSERVICOSPEDEFD         SERIENFSUBCONTRATANTE  VARCHAR2(5)                                         Série da NF  da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD          NUMDOCSUBCONTRATANTE VARCHAR2(30)                                 Número do Documento  da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD     DTEMISSAONFSUBCONTRATANTE         DATE                                  Data de emissão NF  da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD    VALORBRUTONFSUBCONTRATANTE NUMBER(14,2)                                         Valor Bruto  da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD    VALORBASERETSUBCONTRATANTE NUMBER(14,2)                           Valor da Base da Retenção  da empresa Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD        VALORRETSUBCONTRATANTE NUMBER(14,2)                                               Valor da Retenção Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD     CODTIPOSERVSUBCONTRATANTE  VARCHAR2(8)                                             Tipo de Serviços da Subcontratada            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                  TIPOPROCESSO VARCHAR2(30)                                                              Tipo do processo            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                   NUMPROCESSO VARCHAR2(30)                                                               Número processo            OPERACIONAL                        NaN
PCSERVICOSPEDEFD                 VALORRETENCAO NUMBER(14,2)                                                             Valor da retenção            OPERACIONAL                        NaN
PCSERVICOSPEDEFD             CODINDICSUSPENSAO VARCHAR2(14)                                                        código indice supensão            OPERACIONAL                        NaN
PCSERVICOSPEDEFD               NUMPROCESSOADIC VARCHAR2(30)                                                     número processo adicional            OPERACIONAL                        NaN
PCSERVICOSPEDEFD              TIPOPROCESSOADIC VARCHAR2(30)                                                       tipo processo adicional            OPERACIONAL                        NaN
PCSERVICOSPEDEFD         CODINDICSUSPENSAOADIC VARCHAR2(14)                                              código indice supensão adicional            OPERACIONAL                        NaN
PCSERVICOSPEDEFD            VALORINSSNAORETIDO NUMBER(14,2)                                                      Valor de INSS não retido            OPERACIONAL                        NaN
PCSERVICOSPEDEFD        HOUVEVALORRETENCAOINSS  VARCHAR2(1)                                                  Houve valor retenção de INSS            OPERACIONAL                        NaN
PCSERVICOSPEDEFD         CODIGONACIONALDEOBRAS VARCHAR2(12)                                        Informação do código nacional de obras            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*