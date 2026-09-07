# 📊 Tabela: PCLOGPESAGEM

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPESAGEM      NUMPED NUMBER(10,0)          Número do pedido.            OPERACIONAL                        NaN
PCLOGPESAGEM     CODPROD  NUMBER(6,0)  Código do produto pesado.            OPERACIONAL                        NaN
PCLOGPESAGEM          QT NUMBER(20,6)              Qtde. pesada.            OPERACIONAL                        NaN
PCLOGPESAGEM     USUARIO VARCHAR2(60) Usuario que fez a pesagem.            OPERACIONAL                        NaN
PCLOGPESAGEM DATAPESAGEM         DATE    Data e hora da pesagem.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*