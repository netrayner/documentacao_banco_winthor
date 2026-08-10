# 📊 Tabela: PCAJUSTEPERSONALIZADOFILTROS

### Estrutura de Colunas e Restrições

                      Tabela            Coluna   Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAJUSTEPERSONALIZADOFILTROS CODCADASTROAJUSTE    NUMBER(9,0)               Código do registro principal            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOFILTROS          REGISTRO   VARCHAR2(15)               Identifica o tpo do registro            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOFILTROS             CAMPO   VARCHAR2(20) Identifica o campo  que está sendo gravado            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOFILTROS       VALOR_TEXTO VARCHAR2(1000)            Define o valor no formato texto            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOFILTROS        VALOR_DATA           DATE             Define o valor no formato Data            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOFILTROS         VALOR_NUM   NUMBER(20,6)           Define o valor no formato Numero            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*