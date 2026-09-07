# 📊 Tabela: PCMOVSAID

### Estrutura de Colunas e Restrições

   Tabela        Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVSAID     CODFILIAL  VARCHAR2(2)                          Cód.Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSAID   NUMTRANSENT NUMBER(10,0)                   Num.Trans.Entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSAID NUMTRANSVENDA NUMBER(10,0)                     Num.Trans.Saida.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSAID       CODPROD  NUMBER(6,0)                         Cód.Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSAID          DATA         DATE                                Data.            OPERACIONAL                        NaN
PCMOVSAID        QTCONT NUMBER(20,6)                            Qt.saída.            OPERACIONAL                        NaN
PCMOVSAID     NUMSEQENT  NUMBER(5,0) Número sequencial do item na entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*