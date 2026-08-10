# 📊 Tabela: PCCADASTROCNAE

### Estrutura de Colunas e Restrições

        Tabela     Coluna   Tipo/Tamanho Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCADASTROCNAE     CODIGO   NUMBER(10,0)   Código sequencial    CHAVE PRIMÁRIA (PK)                        NaN
PCCADASTROCNAE  DESCRICAO VARCHAR2(1000)   Descrição do CNAE            OPERACIONAL                        NaN
PCCADASTROCNAE       CNAE VARCHAR2(1000)         Código CNAE            OPERACIONAL                        NaN
PCCADASTROCNAE        NCM   VARCHAR2(60)          Código NCM            OPERACIONAL                        NaN
PCCADASTROCNAE   ALIQUOTA   NUMBER(18,2) Alíquota Referencia            OPERACIONAL                        NaN
PCCADASTROCNAE     MESANO    VARCHAR2(7)  Mês/Ano Referencia            OPERACIONAL                        NaN
PCCADASTROCNAE CODIGOCNAE    VARCHAR2(8)                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*