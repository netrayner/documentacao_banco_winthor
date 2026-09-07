# 📊 Tabela: PCFILAMAISNEGENVIO

### Estrutura de Colunas e Restrições

            Tabela         Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILAMAISNEGENVIO             ID VARCHAR2(240)                           ID da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCFILAMAISNEGENVIO      TRANSACAO  NUMBER(10,0) Número do pedido da PCPEDC ou PCNFSAID            OPERACIONAL                        NaN
PCFILAMAISNEGENVIO         FILIAL   VARCHAR2(2)                       Código da Filial            OPERACIONAL                        NaN
PCFILAMAISNEGENVIO  TIPOTRANSACAO  VARCHAR2(20)     Pedido, Nota, Cancelamento de Nota            OPERACIONAL                        NaN
PCFILAMAISNEGENVIO DTHORAOPERACAO  TIMESTAMP(6)                Data e hora da operação            OPERACIONAL                        NaN
PCFILAMAISNEGENVIO       OPERACAO   NUMBER(1,0)           Codigo da operação realizada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*