# 📊 Tabela: PCINTEGRACAOEMPRESAFILIAL

### Estrutura de Colunas e Restrições

                   Tabela                Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOEMPRESAFILIAL                  NOME VARCHAR2(255)                                           Nome da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL                    ID  NUMBER(10,0)                                 Chave primária da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOEMPRESAFILIAL      CODEMPRESAFILIAL VARCHAR2(255)                                         Código da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL      CODFILIALEXTERNO VARCHAR2(255)                                 Código externo da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL                 ATIVO   VARCHAR2(1)                     Indica se a filial está ativa ou não.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL               URLBASE VARCHAR2(512)                                       URL base da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL          REFRESHTOKEN          CLOB                                  Refhesh Token da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL           ACCESSTOKEN          CLOB                                   Access Token da filial.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL ACCESSTOKENEXPIRESINT  NUMBER(10,0)                              Tempo de expiração do token.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL             DTCRIACAO          DATE                              Data de criação do registro.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL         DTATUALIZACAO          DATE                          Data de atualização do registro.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL    DTSOLICITACAOTOKEN          DATE                             Data de solicitação do token.            OPERACIONAL                        NaN
PCINTEGRACAOEMPRESAFILIAL             IDEMPRESA  NUMBER(10,0) Chave estrangeira para a tabela PCINTEGRACAODADOSEMPRESA. CHAVE ESTRANGEIRA (FK)   PCINTEGRACAODADOSEMPRESA

---
*Documentação gerada automaticamente.*