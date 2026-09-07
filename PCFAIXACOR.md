# 📊 Tabela: PCFAIXACOR

### Estrutura de Colunas e Restrições

    Tabela    Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFAIXACOR  CODFAIXA  NUMBER(6,0)                     Código    CHAVE PRIMÁRIA (PK)                        NaN
PCFAIXACOR    CODCOR VARCHAR2(20) Código da Cor para a faixa            OPERACIONAL                        NaN
PCFAIXACOR VLRINICIO NUMBER(16,4)            Inicio da Faixa            OPERACIONAL                        NaN
PCFAIXACOR  VLRFINAL NUMBER(16,4)             Final da Faixa            OPERACIONAL                        NaN
PCFAIXACOR  TIPOVEND  VARCHAR2(2)           Tipo de vendedor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*