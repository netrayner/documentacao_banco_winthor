# 📊 Tabela: PCPAIFILHO

### Estrutura de Colunas e Restrições

    Tabela        Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPAIFILHO       CODOPER  VARCHAR2(2) Tipo da operação que está sendo realizada\t\t\t            OPERACIONAL                        NaN
PCPAIFILHO       CODPROD  VARCHAR2(6)                               Código do produto            OPERACIONAL                        NaN
PCPAIFILHO   NUMTRANSENT NUMBER(10,0)                  Número da Transação de Entrada            OPERACIONAL                        NaN
PCPAIFILHO NUMTRANSVENDA NUMBER(10,0)                    Número da Transação de Saida            OPERACIONAL                        NaN
PCPAIFILHO        NUMPED NUMBER(10,0)                                Número do pedido            OPERACIONAL                        NaN
PCPAIFILHO            QT NUMBER(20,6)                Quantidade do produto convertido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*