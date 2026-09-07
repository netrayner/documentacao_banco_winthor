# 📊 Tabela: PCFORMULACONTABIL

### Estrutura de Colunas e Restrições

           Tabela           Coluna   Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULACONTABIL    CODIGOFORMULA   NUMBER(10,0)      Código do índice contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULACONTABIL        DESCRICAO   VARCHAR2(60)   Descrição do índice contabil            OPERACIONAL                        NaN
PCFORMULACONTABIL    CODPLANOCONTA    NUMBER(5,0)      Códido do plano de contas            OPERACIONAL                        NaN
PCFORMULACONTABIL          FORMULA VARCHAR2(2000) Formula definida para o índice            OPERACIONAL                        NaN
PCFORMULACONTABIL    CODTIPOINDICE   NUMBER(10,0)                            NaN CHAVE ESTRANGEIRA (FK)       PCTIPOINDICECONTABIL
PCFORMULACONTABIL CODFAIXACONTABIL   NUMBER(10,0)       Código da faixa contabil            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*