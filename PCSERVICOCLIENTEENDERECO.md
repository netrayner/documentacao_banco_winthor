# 📊 Tabela: PCSERVICOCLIENTEENDERECO

### Estrutura de Colunas e Restrições

                  Tabela                       Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTEENDERECO                        FONTE VARCHAR2(255)                 Fonte de origem deste endereço            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                   LOGRADOURO VARCHAR2(255)                                     Logradouro            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                  COMPLEMENTO VARCHAR2(255)                        Complemento do endereço            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                       NUMERO  VARCHAR2(50)                                         Número            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                       BAIRRO VARCHAR2(255)                Código identificador do serviço            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                       CIDADE VARCHAR2(255)                                         Cidade            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                       ESTADO VARCHAR2(255)                                         Estado            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                          CEP VARCHAR2(255)                                            CEP            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                   CODIGOIBGE  NUMBER(10,0)                                    Código ibge            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO        DATAALTERACAOCADASTRO          DATE       Data de alteração do cadastro de cliente            OPERACIONAL                        NaN
PCSERVICOCLIENTEENDERECO                  CODENDERECO  NUMBER(10,0)            Código de identificação do endereço    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOCLIENTEENDERECO                   CODCLIENTE  NUMBER(10,0)                Codigo identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTEENDERECO RESPONSAVELALTERACAOCADASTRO VARCHAR2(255) Nome do responsavel pela alteração do cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*