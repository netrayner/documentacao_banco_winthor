# 📊 Tabela: PCESTOQUEDEPOSITOPROD

### Estrutura de Colunas e Restrições

               Tabela       Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTOQUEDEPOSITOPROD    CODFILIAL  VARCHAR2(2)                      Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTOQUEDEPOSITOPROD  CODDEPOSITO NUMBER(10,0)                    Código do Depósito    CHAVE PRIMÁRIA (PK)                        NaN
PCESTOQUEDEPOSITOPROD      CODPROD  NUMBER(6,0)                     Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTOQUEDEPOSITOPROD    QTESTOQUE NUMBER(22,8)                         Qtde. Estoque            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD  QTRESERVADA NUMBER(22,8)               Qtde. Estoque Reservado            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD   QTPENDENTE NUMBER(22,8)                Qtde. Estoque Pendente            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD  QTBLOQUEADA NUMBER(22,8)               Qtde. Estoque Bloqueado            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD QTINDENIZADA NUMBER(22,8)                Qtde. Estoque Avariado            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD       DTLANC         DATE              Dt. Lançamento/Alteração            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD  CODFUNCLANC  NUMBER(8,0)       Cod. Func. Lançamento/Alteração            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD     QTMINIMA NUMBER(22,8) Qtde. minima para o item do depósito.            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD     QTMAXIMA NUMBER(22,8) Qtde. maxima para o item do depósito.            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD  CODAUXILIAR NUMBER(20,0)      Cód. Barras do item do depósito.            OPERACIONAL                        NaN
PCESTOQUEDEPOSITOPROD      NUMLOTE VARCHAR2(15)      Nr. do lote do item do depósito.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*