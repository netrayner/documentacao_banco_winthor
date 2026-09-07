# 📊 Tabela: PCAUTLICENCA

### Estrutura de Colunas e Restrições

      Tabela          Coluna Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTLICENCA          CODCLI  NUMBER(6,0)                                                       Código do cliente PC    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTLICENCA IDBANCOPRODUCAO VARCHAR2(50)                                           ID do banco de dados de produção            OPERACIONAL                        NaN
PCAUTLICENCA    IDBANCOTESTE VARCHAR2(50)                                              ID do banco de dados de teste            OPERACIONAL                        NaN
PCAUTLICENCA          DTCNPJ         DATE                              Data de expiração do CNPJ não registros na PC            OPERACIONAL                        NaN
PCAUTLICENCA   PERIODICIDADE  NUMBER(6,0) Periodicidade que será feito a atualização dos dados da licença no cliente            OPERACIONAL                        NaN
PCAUTLICENCA     TIPOCLIENTE VARCHAR2(15)                                                Tipo de cliente / Categoria            OPERACIONAL                        NaN
PCAUTLICENCA      TIPOVERSAO  NUMBER(1,0)                               Tipo da versão das rotintas (Aberto/Fechado)            OPERACIONAL                        NaN
PCAUTLICENCA     RAZAOSOCIAL VARCHAR2(60)                                                    Razão social do cliente            OPERACIONAL                        NaN
PCAUTLICENCA    NOMEFANTASIA VARCHAR2(40)                                                              Nome fantasia            OPERACIONAL                        NaN
PCAUTLICENCA          CIDADE VARCHAR2(15)                                                                     Cidade            OPERACIONAL                        NaN
PCAUTLICENCA          ESTADO  VARCHAR2(2)                                                                        NaN            OPERACIONAL                        NaN
PCAUTLICENCA     DTEXPIRACAO         DATE                                                             Data Expiração            OPERACIONAL                        NaN
PCAUTLICENCA      DTEXCLUSAO         DATE                                                                        NaN            OPERACIONAL                        NaN
PCAUTLICENCA     DLLGERADORA  NUMBER(4,0)                                                                        NaN            OPERACIONAL                        NaN
PCAUTLICENCA   IDBANCOTESTE2 VARCHAR2(40)                                                                        NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*