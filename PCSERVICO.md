# 📊 Tabela: PCSERVICO

### Estrutura de Colunas e Restrições

   Tabela             Coluna  Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICO         CODSERVICO  NUMBER(10,0)                                           Código identificador do serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICO          IDSERVICO VARCHAR2(255)                                    Identificador de fornecedor do serviço            OPERACIONAL                        NaN
PCSERVICO               NOME VARCHAR2(255)                                                           Nome do serviço            OPERACIONAL                        NaN
PCSERVICO          DESCRICAO VARCHAR2(255)                                                      Descrição do serviço            OPERACIONAL                        NaN
PCSERVICO MODELOPRECIFICACAO VARCHAR2(255)                                         Modelo de precificação do serviço            OPERACIONAL                        NaN
PCSERVICO              PRECO VARCHAR2(255)                                  Preço ofertado para aquisição do serviço            OPERACIONAL                        NaN
PCSERVICO       DATAVALIDADE          DATE                                        Data de validade do preço ofertado            OPERACIONAL                        NaN
PCSERVICO          ADQUIRIDO       CHAR(1)          Se o serviço foi adquirido, será igual a "S". Caso contrário "N"            OPERACIONAL                        NaN
PCSERVICO          UTILIZADO       CHAR(1)          Se o serviço foi utilizado, será igual a "S". Caso contrário "N"            OPERACIONAL                        NaN
PCSERVICO      OFERTAEXPIROU       CHAR(1) Se o preço ofertado está expirado, , será igual a "S". Caso contrário "N"            OPERACIONAL                        NaN
PCSERVICO        TIPOSERVICO VARCHAR2(255)                                                 Tipo de serviço adquirido            OPERACIONAL                        NaN
PCSERVICO      DATAAQUISICAO          DATE                                              Data da aquisição do serviço            OPERACIONAL                        NaN
PCSERVICO         QUANTIDADE  NUMBER(10,0)                                        Quantidade de registros adquiridos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*