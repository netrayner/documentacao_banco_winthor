# 📊 Tabela: PCDICIONARIOCONFIGURACAO

### Estrutura de Colunas e Restrições

                  Tabela                     Coluna   Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDICIONARIOCONFIGURACAO  CODDICIONARIOCONFIGURACAO   NUMBER(22,0)                                                              Chave do dicionario de configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCDICIONARIOCONFIGURACAO TIPODICIONARIOCONFIGURACAO   VARCHAR2(50) String que representa o dado de dicionario de configuração de forma mais resumida e programatica            OPERACIONAL                        NaN
PCDICIONARIOCONFIGURACAO         TEMPLATEDICIONARIO VARCHAR2(4000)                      String que contem dados necessários para construção da tela de configuração            OPERACIONAL                        NaN
PCDICIONARIOCONFIGURACAO        CODTIPOCONFIGURACAO    NUMBER(5,0)                                                          FK que liga a tabela PCTIPOCONFIGURACAO CHAVE ESTRANGEIRA (FK)         PCTIPOCONFIGURACAO

---
*Documentação gerada automaticamente.*