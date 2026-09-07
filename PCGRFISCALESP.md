# 📊 Tabela: PCGRFISCALESP

### Estrutura de Colunas e Restrições

       Tabela       Coluna   Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRFISCALESP CODRELATORIO    NUMBER(4,0)                              CÓDIGO DO RELATORIO    CHAVE PRIMÁRIA (PK)                        NaN
PCGRFISCALESP       TITULO  VARCHAR2(200)                              TITULO DO RELATORIO            OPERACIONAL                        NaN
PCGRFISCALESP      TIPOMOV    VARCHAR2(1)         TIPO DE MOVIMENTAÇÃO(E-ENTRADA, S-SAÍDA)            OPERACIONAL                        NaN
PCGRFISCALESP        ORDEM VARCHAR2(1000)                   ORDENAÇÃO DOS CAMPOS(ORDER BY)            OPERACIONAL                        NaN
PCGRFISCALESP      VINCULO    VARCHAR2(1) Vincular entrada a ultima entrada ou metodo PEPS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*