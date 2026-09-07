# 📊 Tabela: PCGMPREMIONIVEL

### Estrutura de Colunas e Restrições

         Tabela      Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPREMIONIVEL      CODIGO NUMBER(10,0)          Código da combinação    CHAVE PRIMÁRIA (PK)             PCGMPREMIOCOMB
PCGMPREMIONIVEL       ORDEM NUMBER(10,0) Ordem da sequencia dos niveis    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPREMIONIVEL PERCINICIAL  NUMBER(8,2)            Percentual inicial            OPERACIONAL                        NaN
PCGMPREMIONIVEL   PERCFINAL  NUMBER(8,2)              Percentual final            OPERACIONAL                        NaN
PCGMPREMIONIVEL        PESO  NUMBER(6,3)                 Peso do nivel            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*