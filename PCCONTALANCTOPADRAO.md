# 📊 Tabela: PCCONTALANCTOPADRAO

### Estrutura de Colunas e Restrições

             Tabela         Coluna  Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTALANCTOPADRAO  CODLANCPADRAO  NUMBER(10,0)   Indica o código do lançamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTALANCTOPADRAO CODREDUZIDO_PC  VARCHAR2(12)         Indica o conta contábil.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTALANCTOPADRAO       NATUREZA   VARCHAR2(1)      Indica a natureza da conta.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTALANCTOPADRAO   CODHISTORICO   NUMBER(4,0)    Indica o código do historico.            OPERACIONAL                        NaN
PCCONTALANCTOPADRAO     HIST_COMPL VARCHAR2(200) Indica o historico complementar.            OPERACIONAL                        NaN
PCCONTALANCTOPADRAO     PERCENTUAL  NUMBER(10,3)    Indica o percentual do valor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*