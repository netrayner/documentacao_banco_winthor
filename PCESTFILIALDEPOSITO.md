# 📊 Tabela: PCESTFILIALDEPOSITO

### Estrutura de Colunas e Restrições

             Tabela      Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTFILIALDEPOSITO NUMTRANSENT NUMBER(10,0)            Numero da transação de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCESTFILIALDEPOSITO   CODFILIAL  VARCHAR2(2)               Codigo da filial do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTFILIALDEPOSITO     CODPROD  NUMBER(6,0)                         Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTFILIALDEPOSITO       QTEST NUMBER(22,8)  Quantidade de estoque contabil na filial            OPERACIONAL                        NaN
PCESTFILIALDEPOSITO    QTESTGER NUMBER(22,8) Quantidade de estoque gerencial na filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*