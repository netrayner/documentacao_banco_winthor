# 📊 Tabela: PCMOVENT

### Estrutura de Colunas e Restrições

  Tabela      Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVENT   CODFILIAL  VARCHAR2(2)                             Código da filial.            OPERACIONAL                        NaN
PCMOVENT NUMTRANSENT NUMBER(10,0)                            Num.Trans.Entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVENT     CODPROD  NUMBER(6,0)                              Código Produto .    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVENT        DATA         DATE                                         Data.            OPERACIONAL                        NaN
PCMOVENT      QTCONT NUMBER(20,6)                                   Qt.Entrada.            OPERACIONAL                        NaN
PCMOVENT       SALDO NUMBER(20,6)                                Saldo Entrada.            OPERACIONAL                        NaN
PCMOVENT      NUMSEQ  NUMBER(5,0) Número sequencial do item referente a entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*