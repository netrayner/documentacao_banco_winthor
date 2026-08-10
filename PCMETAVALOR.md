# 📊 Tabela: PCMETAVALOR

### Estrutura de Colunas e Restrições

     Tabela               Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAVALOR         CODMETAVALOR  NUMBER(6,0)               Cód. oo valor da meta cadastrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAVALOR CODMETAPRODUTIVIDADE  NUMBER(6,0) Cód. da produtividade que meta está relacionada            OPERACIONAL                        NaN
PCMETAVALOR            VLINICIAL NUMBER(20,6)                                   Valor inicial            OPERACIONAL                        NaN
PCMETAVALOR              VLFINAL NUMBER(20,6)                                     Valor final            OPERACIONAL                        NaN
PCMETAVALOR             VLAPAGAR NUMBER(20,6)                                   Valor a pagar            OPERACIONAL                        NaN
PCMETAVALOR                 TIPO  VARCHAR2(1)                                    Tipo de meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*