# 📊 Tabela: PCWMSCODBARRAS

### Estrutura de Colunas e Restrições

        Tabela     Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSCODBARRAS  CODFILIAL  VARCHAR2(2)                     Código da Filial            OPERACIONAL                        NaN
PCWMSCODBARRAS CODPRODUTO  NUMBER(6,0)                    Código do Produto            OPERACIONAL                        NaN
PCWMSCODBARRAS  CODBARRAS VARCHAR2(20)                     Código de Barras            OPERACIONAL                        NaN
PCWMSCODBARRAS  EMBALAGEM VARCHAR2(12)                            Embalagem            OPERACIONAL                        NaN
PCWMSCODBARRAS    UNIDADE  VARCHAR2(2) Indica a unidade do produto (UN, CX)            OPERACIONAL                        NaN
PCWMSCODBARRAS     QTUNIT NUMBER(18,6)          Quantidade de unidade/caixa            OPERACIONAL                        NaN
PCWMSCODBARRAS       TIPO      CHAR(1)                Tipo do Código Barras            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*