# 📊 Tabela: PCREINFGRUPOEMPRESAS

### Estrutura de Colunas e Restrições

              Tabela                   Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFGRUPOEMPRESAS                       ID  NUMBER(8,0)                               Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFGRUPOEMPRESAS                     NOME VARCHAR2(50)                               Nome do grupo            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS         CODEMPRESAMATRIZ  VARCHAR2(2)                    Código da empresa matriz CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCREINFGRUPOEMPRESAS            CERTIFICADOA1         BLOB                  Certificificado digital A1            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS       SENHACERTIFICADOA1 VARCHAR2(70)             Senha do certificado digital A1            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS     AMBIENTEWEBSERVICERF       NUMBER                      Ambiente da webservice            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS CERTIFICADODETRANSMISSAO  VARCHAR2(2) Tipo do certificado de transmissao do REINF            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS            NUMEROSERIEA3 VARCHAR2(50)           Numero de serie do certificado A3            OPERACIONAL                        NaN
PCREINFGRUPOEMPRESAS       SENHACERTIFICADOA3 VARCHAR2(70)                     Senha do certificado A3            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*