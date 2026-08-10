# 📊 Tabela: PCDEVAVARIAI

### Estrutura de Colunas e Restrições

      Tabela        Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEVAVARIAI NUMTRANSVENDA NUMBER(10,0)                     Transação de saída avaria.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEVAVARIAI       CODPROD  NUMBER(6,0) Código do produto que será devolvido em avaria    CHAVE PRIMÁRIA (PK)                        NaN
PCDEVAVARIAI      QTAVARIA NUMBER(20,6)              Qtde. Avariada que será devolvida            OPERACIONAL                        NaN
PCDEVAVARIAI     CODFILIAL  VARCHAR2(2)                                            NaN            OPERACIONAL                        NaN
PCDEVAVARIAI       NUMLOTE VARCHAR2(15)                     Indica o código da filial.            OPERACIONAL                        NaN
PCDEVAVARIAI        NUMSEQ NUMBER(10,0)                Numero de sequencia lançamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCDEVAVARIAI   NUMTRANSENT NUMBER(20,0) Número de transação da Nota Fiscal de Entrada.            OPERACIONAL                        NaN
PCDEVAVARIAI   CODDEPOSITO NUMBER(10,0)                             Código do Depósito            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*