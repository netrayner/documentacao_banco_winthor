# 📊 Tabela: PCBONUSIMPI

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBONUSIMPI     NUMBONUS  NUMBER(6,0)            Numero do Bonus    CHAVE PRIMÁRIA (PK)                        NaN
PCBONUSIMPI      CODPROD  NUMBER(6,0)          Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCBONUSIMPI           QT NUMBER(20,6)       Quantidade dos itens            OPERACIONAL                        NaN
PCBONUSIMPI    CODFORNEC  NUMBER(6,0)       codigo do fornecedor            OPERACIONAL                        NaN
PCBONUSIMPI      CODEPTO  NUMBER(6,0)     codigo do departamento            OPERACIONAL                        NaN
PCBONUSIMPI      NUMLOTE VARCHAR2(15)             numero do lote            OPERACIONAL                        NaN
PCBONUSIMPI       NUMSEQ NUMBER(20,0)        numero de sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCBONUSIMPI   QTDIGITADA NUMBER(20,6)      data que foi digitado            OPERACIONAL                        NaN
PCBONUSIMPI   DTVALIDADE         DATE           data da validade            OPERACIONAL                        NaN
PCBONUSIMPI   QTAVARIADA NUMBER(20,6)        quantidade avariada            OPERACIONAL                        NaN
PCBONUSIMPI DTFABRICACAO         DATE         data de fabricacao            OPERACIONAL                        NaN
PCBONUSIMPI    CODMOTIVO  NUMBER(4,0)           codigo do motivo            OPERACIONAL                        NaN
PCBONUSIMPI       DTCONF         DATE Data da Digitação do Bonus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*