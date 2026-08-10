# 📊 Tabela: PCDESCONTOCATEGORIA

### Estrutura de Colunas e Restrições

             Tabela            Coluna  Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOCATEGORIA            CODIGO  NUMBER(10,0)                                Código da campanha de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA               SEQ  NUMBER(10,0)                            IDENTIFICADOR DA FAIXA DE DESCONTO            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA              TIPO VARCHAR2(100)                                     Tipo de regra de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA         TIPOVALOR  NUMBER(12,6)                                    Valor da regra de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA          PERCDESC  NUMBER(12,6)                                        percentual de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA   INICIOINTERVALO  NUMBER(12,6)                               Início do intervalo de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA      FIMINTERVALO  NUMBER(12,6)                                  Fim do intervalo de desconto            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA   EMBALAGEM_UNICA   VARCHAR2(1) Indica se a campanha valida a unidade comum entre os produtos            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA UNIDADE_EMBALAGEM   VARCHAR2(2)           Indica qual a unidade comum entre todos os produtos            OPERACIONAL                        NaN
PCDESCONTOCATEGORIA        DTMXSALTER          DATE                                                           NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*