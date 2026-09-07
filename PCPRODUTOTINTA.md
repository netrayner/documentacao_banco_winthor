# 📊 Tabela: PCPRODUTOTINTA

### Estrutura de Colunas e Restrições

        Tabela                 Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOTINTA             CODMAQUINA  NUMBER(4,0)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOTINTA               CODLINHA VARCHAR2(40)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOTINTA           CODPRODTINTA VARCHAR2(40)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOTINTA               CODTCOMP  VARCHAR2(2)                               NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOTINTA               DESCPROD VARCHAR2(70)                               NaN            OPERACIONAL                        NaN
PCPRODUTOTINTA         PESOESPECIFICO NUMBER(10,6)                               NaN            OPERACIONAL                        NaN
PCPRODUTOTINTA   CAPACIDADEVOLUMELATA NUMBER(18,6)                               NaN            OPERACIONAL                        NaN
PCPRODUTOTINTA         CODPRODWINTHOR  NUMBER(6,0)                               NaN            OPERACIONAL                        NaN
PCPRODUTOTINTA                   TIPO  VARCHAR2(1)                               NaN            OPERACIONAL                        NaN
PCPRODUTOTINTA            CODBASETIPO VARCHAR2(10)        CÓD. DO TIPO BASE DA TINTA            OPERACIONAL                        NaN
PCPRODUTOTINTA       CODAUXILIARTINTA VARCHAR2(20)          CÓDIGO AUXILIAR DA TINTA            OPERACIONAL                        NaN
PCPRODUTOTINTA DESCONSIDERARPIGMENTOS  VARCHAR2(1) DESCONSIDERAR PREÇO DOS PIGMENTOS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*