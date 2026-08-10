# 📊 Tabela: PCGIRODIAMEMORIA

### Estrutura de Colunas e Restrições

          Tabela    Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIAMEMORIA   CODPROD NUMBER(10,0)                             Codigo do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAMEMORIA CODFILIAL  VARCHAR2(2)                              Codigo da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAMEMORIA      JSON         CLOB           Memória de cálculo completa em JSON            OPERACIONAL                        NaN
PCGIRODIAMEMORIA  DATAHORA         DATE Data e hora do momento da gravação da memoria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*