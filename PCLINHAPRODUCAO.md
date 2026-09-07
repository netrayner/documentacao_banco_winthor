# 📊 Tabela: PCLINHAPRODUCAO

### Estrutura de Colunas e Restrições

         Tabela      Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLINHAPRODUCAO    CODLINHA  NUMBER(8,0)    Código da Linha de Produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCLINHAPRODUCAO   DESCRICAO VARCHAR2(40) Descrição da linha de produção.            OPERACIONAL                        NaN
PCLINHAPRODUCAO CODFUNCLANC  NUMBER(8,0)    Usuário resp. pelo cadastro.            OPERACIONAL                        NaN
PCLINHAPRODUCAO      DTLANC         DATE               Data de cadastro.            OPERACIONAL                        NaN
PCLINHAPRODUCAO   CODFILIAL  VARCHAR2(2)               Código de Filial.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*