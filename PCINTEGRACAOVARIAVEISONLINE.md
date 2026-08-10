# 📊 Tabela: PCINTEGRACAOVARIAVEISONLINE

### Estrutura de Colunas e Restrições

                     Tabela          Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOVARIAVEISONLINE           CHAVE VARCHAR2(40)                        Chave da variável online.            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEISONLINE       TIPOCHAVE VARCHAR2(20)                 Tipo da chave da variável online            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEISONLINE       TIPOVALOR VARCHAR2(20)                Tipo do valor da variável online.            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEISONLINE   IDFLUXOONLINE NUMBER(10,0) Id do registro na tabela pcintegracaofluxoonline CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOFLUXOONLINE
PCINTEGRACAOVARIAVEISONLINE   IDROTASERVICO NUMBER(10,0)                   Id da rota da variável online. CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOROTASERVICO
PCINTEGRACAOVARIAVEISONLINE           VALOR         CLOB                        Valor da variável online.            OPERACIONAL                        NaN
PCINTEGRACAOVARIAVEISONLINE              ID NUMBER(10,0)                                  Id do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOVARIAVEISONLINE IDEMPRESAFILIAL NUMBER(10,0) Id da empresa filial a qual a variável pertence.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*