# 📊 Tabela: PCGRUPOSCAMPANHAC

### Estrutura de Colunas e Restrições

           Tabela        Coluna  Tipo/Tamanho                                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOSCAMPANHAC      CODGRUPO   NUMBER(6,0)                                                                                              Código do grupo.    CHAVE PRIMÁRIA (PK)                        NaN
PCGRUPOSCAMPANHAC          TIPO   VARCHAR2(2)                                                                                                Tipo do grupo.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC     CODFILIAL   VARCHAR2(2)                                                                                       Código filial do grupo.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC     DESCRICAO VARCHAR2(100)                                                                                           Descrição do grupo.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC    DTEXCLUSAO          DATE                                                                                       Data exclusão do grupo.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC    DTINCLUSAO          DATE                                                                                       Data inclusão do grupo.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC       CODFUNC   NUMBER(8,0)                                                                                           Código funcionário.            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC    DTMXSALTER          DATE                                                                                                           NaN            OPERACIONAL                        NaN
PCGRUPOSCAMPANHAC DATAALTERACAO          DATE Data de alteração, caso algum registro seja inserido e/ ou alterado na tabela, independente do tipo do grupo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*