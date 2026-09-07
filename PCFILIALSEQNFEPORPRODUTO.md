# 📊 Tabela: PCFILIALSEQNFEPORPRODUTO

### Estrutura de Colunas e Restrições

                  Tabela       Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILIALSEQNFEPORPRODUTO     CODGRUPO  NUMBER(10,0)                 Código do grupo    CHAVE PRIMÁRIA (PK)                        NaN
PCFILIALSEQNFEPORPRODUTO    DESCRICAO VARCHAR2(120)              Descrição do grupo            OPERACIONAL                        NaN
PCFILIALSEQNFEPORPRODUTO    CODFILIAL   VARCHAR2(2) Código da filial do agrupamento CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCFILIALSEQNFEPORPRODUTO  PROXNUMNOTA  NUMBER(10,0)      Próximo sequencial da nota            OPERACIONAL                        NaN
PCFILIALSEQNFEPORPRODUTO PROXNUMSERIE  NUMBER(10,0)     Próximo sequencial da série            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*