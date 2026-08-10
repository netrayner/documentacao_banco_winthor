# 📊 Tabela: PCRESTRICAOTIPOENTFILIAL

### Estrutura de Colunas e Restrições

                  Tabela         Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAOTIPOENTFILIAL      CODFILIAL  VARCHAR2(2) Código da filial para restrição do tipo de entrega            OPERACIONAL                        NaN
PCRESTRICAOTIPOENTFILIAL    TIPOENTREGA  VARCHAR2(2)            Restrição de tipo de entrega por filial            OPERACIONAL                        NaN
PCRESTRICAOTIPOENTFILIAL       PERMITIR  VARCHAR2(1)        Permitir ou não o tipo de entrega na filial            OPERACIONAL                        NaN
PCRESTRICAOTIPOENTFILIAL        CODPROD  NUMBER(6,0)                                  Código do produto            OPERACIONAL                        NaN
PCRESTRICAOTIPOENTFILIAL VENDAASSISTIDA  VARCHAR2(1)                      Informar se é Venda assistida            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*