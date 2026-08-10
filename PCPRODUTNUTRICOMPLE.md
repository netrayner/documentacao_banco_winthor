# 📊 Tabela: PCPRODUTNUTRICOMPLE

### Estrutura de Colunas e Restrições

             Tabela            Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTNUTRICOMPLE       CODAUXILIAR NUMBER(16,0)                             Código auxiliar    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTNUTRICOMPLE            PORCAO VARCHAR2(35)                         Porção da embalagem    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTNUTRICOMPLE      NOMEINFNUTRI VARCHAR2(60)              Nome da informação nutricional    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTNUTRICOMPLE          QTPORCAO  NUMBER(8,3)                        Quantidade da porção            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE       VALORDIARIO  NUMBER(8,3)                    Valor diário recomendado            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE          UNMEDIDA VARCHAR2(40) Unidade de medida do componente nutricional            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE       CODUNMEDIDA  VARCHAR2(1)         Código da unidade de medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE      QTMEDCASEIRA  VARCHAR2(2)     Quantidade da unidade de medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE PARTDECMEDCASEIRA  VARCHAR2(1)             Parte decimal da medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE    NOMEMEDCASEIRA VARCHAR2(30)                         Nome medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRICOMPLE     CODMEDCASEIRA  VARCHAR2(2)                       Código medida caseira            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*