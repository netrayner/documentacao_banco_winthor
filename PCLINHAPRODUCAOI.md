# 📊 Tabela: PCLINHAPRODUCAOI

### Estrutura de Colunas e Restrições

          Tabela       Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLINHAPRODUCAOI     CODLINHA  NUMBER(8,0) Código da Linha de Produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCLINHAPRODUCAOI      CODPROD  NUMBER(6,0)           Código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCLINHAPRODUCAOI  CODFUNCLANC  NUMBER(8,0) Usuário resp. pelo cadastro.            OPERACIONAL                        NaN
PCLINHAPRODUCAOI       DTLANC         DATE            Data de cadastro.            OPERACIONAL                        NaN
PCLINHAPRODUCAOI    CODFILIAL  VARCHAR2(2)            Código de Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLINHAPRODUCAOI CODFUNCLIDER  NUMBER(8,0) Código do funcionário lider.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*