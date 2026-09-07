# 📊 Tabela: PCHISTMOVENT

### Estrutura de Colunas e Restrições

      Tabela        Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTMOVENT     CODFILIAL  VARCHAR2(2)               Código Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTMOVENT   NUMTRANSENT NUMBER(10,0)           Num.Trans.Entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTMOVENT       CODPROD  NUMBER(6,0)              Código Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTMOVENT       DTSAIDA         DATE                        Data.    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTMOVENT        QTCONT NUMBER(20,6)                  Qt.Entrada.            OPERACIONAL                        NaN
PCHISTMOVENT         SALDO NUMBER(20,6)               Saldo Entrada.            OPERACIONAL                        NaN
PCHISTMOVENT NUMTRANSVENDA NUMBER(10,0) NUMERO DE TRANSAÇÃO DE VENDA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*