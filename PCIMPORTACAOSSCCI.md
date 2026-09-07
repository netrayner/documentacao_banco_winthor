# 📊 Tabela: PCIMPORTACAOSSCCI

### Estrutura de Colunas e Restrições

           Tabela         Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCIMPORTACAOSSCCI ID_GRUPO_CAIXA VARCHAR2(14)                  ID do grupo de caixa importado            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI    EAN_PRODUTO VARCHAR2(20)                        Ean do produto importado            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI  QT_PROD_CAIXA NUMBER(10,0)             Quantidade do produto em cada caixa            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI        QT_CONF NUMBER(10,0)  Quantidade conferida de cada produto importado            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI        CODCONF  NUMBER(4,0)    Código do usuário que realizou a conferência            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI      DATA_CONF         DATE Data em que foi realizada a conferência do item            OPERACIONAL                        NaN
PCIMPORTACAOSSCCI        CODPROD  NUMBER(6,0)                     Código do produto importado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*