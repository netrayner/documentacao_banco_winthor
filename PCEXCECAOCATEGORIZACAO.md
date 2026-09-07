# 📊 Tabela: PCEXCECAOCATEGORIZACAO

### Estrutura de Colunas e Restrições

                Tabela    Coluna  Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOCATEGORIZACAO    CODIGO  NUMBER(10,0)                                                     Código identificado do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOCATEGORIZACAO DESCRICAO VARCHAR2(120)                                                   Descrição da categoria da exceção            OPERACIONAL                        NaN
PCEXCECAOCATEGORIZACAO      ACAO   VARCHAR2(1) Ação a ser tomada, na exceção (C = Considerar/ D = Desconsiderar/ R = Redirecionar)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*