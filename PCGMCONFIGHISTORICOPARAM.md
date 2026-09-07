# 📊 Tabela: PCGMCONFIGHISTORICOPARAM

### Estrutura de Colunas e Restrições

                  Tabela          Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMCONFIGHISTORICOPARAM          CODIGO NUMBER(10,0) Código sequêncial da configuração do historico da parametrização    CHAVE PRIMÁRIA (PK)                        NaN
PCGMCONFIGHISTORICOPARAM    CODPARAMMETA NUMBER(10,0)    código da parametrização que ira utilizar os dados histórivos CHAVE ESTRANGEIRA (FK)              PCGMPARAMMETA
PCGMCONFIGHISTORICOPARAM     CODTIPOMETA NUMBER(10,0)                    código do tipo de meta referente a combinação            OPERACIONAL                        NaN
PCGMCONFIGHISTORICOPARAM    CODINDICADOR NUMBER(10,0)                       Código do indicador referente a combinação            OPERACIONAL                        NaN
PCGMCONFIGHISTORICOPARAM CODENTIDADEMETA NUMBER(10,0)                                    Código da meta do colaborador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*