# 📊 Tabela: PCGRFISCAL

### Estrutura de Colunas e Restrições

    Tabela       Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRFISCAL CODRELATORIO    NUMBER(4,0)                      Código do Relatório    CHAVE PRIMÁRIA (PK)                        NaN
PCGRFISCAL       TITULO  VARCHAR2(200)                      Título do Relatório            OPERACIONAL                        NaN
PCGRFISCAL      TIPOMOV    VARCHAR2(1) Tipo de Movimentação(E-Entrada, S-Saída)            OPERACIONAL                        NaN
PCGRFISCAL        ORDEM VARCHAR2(1000)           Ordenação dos Campos(ORDER BY)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*