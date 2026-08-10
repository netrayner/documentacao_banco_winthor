# 📊 Tabela: PCCATEGORIAWEB

### Estrutura de Colunas e Restrições

        Tabela       Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATEGORIAWEB CODCATEGORIA  NUMBER(10,0)       Codigo da Categoria    CHAVE PRIMÁRIA (PK)                        NaN
PCCATEGORIAWEB    DESCRICAO VARCHAR2(100)    Descrição da Categoria            OPERACIONAL                        NaN
PCCATEGORIAWEB     CODSECAO  NUMBER(10,0)           Codigo da Seção            OPERACIONAL                        NaN
PCCATEGORIAWEB  SITUACAOWEB   VARCHAR2(1)               VARCHAR2(1)            OPERACIONAL                        NaN
PCCATEGORIAWEB   DTCADASTRO          DATE          Data de cadastro            OPERACIONAL                        NaN
PCCATEGORIAWEB   DTULTALTER          DATE Data de ultima alteração             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*