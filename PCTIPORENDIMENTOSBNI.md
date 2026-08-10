# 📊 Tabela: PCTIPORENDIMENTOSBNI

### Estrutura de Colunas e Restrições

              Tabela            Coluna   Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPORENDIMENTOSBNI CODTIPORENDIMENTO   NUMBER(10,0) Não\tCódigo natureza do rendimento    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPORENDIMENTOSBNI         DESCRICAO VARCHAR2(1000)             Natureza de rendimento            OPERACIONAL                        NaN
PCTIPORENDIMENTOSBNI RENDIMENTO_ISENTO  VARCHAR2(100)     Códigos de Rendimentos Isentos            OPERACIONAL                        NaN
PCTIPORENDIMENTOSBNI           TRIBUTO  VARCHAR2(100)                Códigos de tributos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*