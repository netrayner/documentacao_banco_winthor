# 📊 Tabela: PCESTPAF

### Estrutura de Colunas e Restrições

  Tabela    Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTPAF   CODPROD   NUMBER(6,0)                 Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTPAF     QTEST  NUMBER(22,8)        Quantidade produto estoque            OPERACIONAL                        NaN
PCESTPAF CODFILIAL   VARCHAR2(2)                  Codigo da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTPAF    MD5PAF VARCHAR2(200) Assinatura MD5 do registro do PAF            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*