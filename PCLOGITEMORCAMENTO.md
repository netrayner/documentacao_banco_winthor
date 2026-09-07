# 📊 Tabela: PCLOGITEMORCAMENTO

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGITEMORCAMENTO          TIPO  VARCHAR2(1) Tipo do orçamento(Dav, Pre-Venda, Ficha)            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO       NUMORCA NUMBER(13,0)                      Número do orçamento            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO   DTALTERACAO         DATE                        Data da alteração            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO HORAALTERACAO  VARCHAR2(8)                           Hora alteração            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO   CODAUXILIAR NUMBER(14,0)                          Código auxiliar            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO          QTDE  NUMBER(6,3)                       Quantidade vendida            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO         VALOR NUMBER(12,2)                            Preço produto            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO      DESCONTO NUMBER(12,2)                         Desconto produto            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO     ACRESCIMO NUMBER(12,2)                        Acrescimo produto            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO      ALIQUOTA  VARCHAR2(6)                      Aliquota do produto            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO     CANCELADO  VARCHAR2(1)                Indicador de Cancelamento            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO TIPOALTERACAO  VARCHAR2(1)                        Tipo da alteração            OPERACIONAL                        NaN
PCLOGITEMORCAMENTO     CODFILIAL  VARCHAR2(6)                         Código da filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*