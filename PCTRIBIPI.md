# 📊 Tabela: PCTRIBIPI

### Estrutura de Colunas e Restrições

   Tabela            Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBIPI         CODFILIAL  VARCHAR2(2)                                  Código da Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBIPI           CODPROD  NUMBER(6,0)                                 Código do Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBIPI  CODSITTRIBIPIENT  NUMBER(3,0) Código da Situação Tributária de IPI nas Entradas.            OPERACIONAL                        NaN
PCTRIBIPI CODSITTRIBIPISAID  NUMBER(3,0)   Código da Situação Tributária de IPI nas Saídas.            OPERACIONAL                        NaN
PCTRIBIPI      CODFIGURAIPI  NUMBER(8,0)                        Código da Figura Tributária            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*