# 📊 Tabela: PCPARCELASI

### Estrutura de Colunas e Restrições

     Tabela     Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARCELASI CODPARCELA  NUMBER(6,0) Código de relacionamento com a tabela PCPARCELASC, não é sequencial.  CHAVE ESTRANGEIRA (FK)                PCPARCELASC
PCPARCELASI      PRAZO  NUMBER(5,0)         Número de dias decorrente a data base informado pela rotina.             OPERACIONAL                        NaN
PCPARCELASI SEQPARCELA  NUMBER(3,0)                                            Sequêncial do parcelamento            OPERACIONAL                        NaN
PCPARCELASI   PERCPESO  NUMBER(7,4)                            Peso da parcela com relação ao valor total            OPERACIONAL                        NaN
PCPARCELASI  CALCIPIST  VARCHAR2(1)                               Calcular Impostos (ST e IPI) na Parcela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*