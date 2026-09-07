# 📊 Tabela: PCTIPORENDIMENTOSPEDIRPJ

### Estrutura de Colunas e Restrições

                  Tabela            Coluna   Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPORENDIMENTOSPEDIRPJ CODTIPORENDIMENTO   NUMBER(10,0)       Código natureza do rendimento    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPORENDIMENTOSPEDIRPJ         DESCRICAO VARCHAR2(1000) Descrição da Natureza de rendimento            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPJ               DED  VARCHAR2(100)                 Códigos de Deduções            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPJ RENDIMENTO_ISENTO  VARCHAR2(100)                 Rendimentos Isentos            OPERACIONAL                        NaN
PCTIPORENDIMENTOSPEDIRPJ           TRIBUTO  VARCHAR2(100)                 Códigos de tributos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*