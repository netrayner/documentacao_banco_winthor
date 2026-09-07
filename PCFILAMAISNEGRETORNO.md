# 📊 Tabela: PCFILAMAISNEGRETORNO

### Estrutura de Colunas e Restrições

              Tabela         Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILAMAISNEGRETORNO             ID VARCHAR2(240)                           ID da tabela            OPERACIONAL                        NaN
PCFILAMAISNEGRETORNO      TRANSACAO  NUMBER(10,0) Número do pedido da PCPEDC ou PCNFSAID            OPERACIONAL                        NaN
PCFILAMAISNEGRETORNO         FILIAL   VARCHAR2(2)                       Código da Filial            OPERACIONAL                        NaN
PCFILAMAISNEGRETORNO       OPERACAO   NUMBER(1,0)    Inclusão, Alteração ou Cancelamento            OPERACIONAL                        NaN
PCFILAMAISNEGRETORNO DTHORAOPERACAO  TIMESTAMP(6)                Data e hora da operação            OPERACIONAL                        NaN
PCFILAMAISNEGRETORNO  TIPOTRANSACAO  VARCHAR2(20)    Tipo transação que ocorrerá retorno            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*