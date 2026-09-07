# 📊 Tabela: PCCONTROLEITEMLIVROFISCAL

### Estrutura de Colunas e Restrições

                   Tabela    Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLEITEMLIVROFISCAL CODFILIAL  VARCHAR2(2)               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEITEMLIVROFISCAL       ANO  NUMBER(4,0) Ano do Encerramento/Reabertura    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEITEMLIVROFISCAL       MES  NUMBER(2,0) Mês do Encerramento/Reabertura    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEITEMLIVROFISCAL       DIA  NUMBER(2,0) Dia do Encerramento/Reabertura    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEITEMLIVROFISCAL ENCERRADO  VARCHAR2(1)            Encerramento do dia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*