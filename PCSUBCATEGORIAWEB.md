# 📊 Tabela: PCSUBCATEGORIAWEB

### Estrutura de Colunas e Restrições

           Tabela          Coluna  Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUBCATEGORIAWEB CODSUBCATEGORIA  NUMBER(15,0)     Codigo Sub categoria    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIAWEB       DESCRICAO VARCHAR2(100)  Descrição Sub categoria            OPERACIONAL                        NaN
PCSUBCATEGORIAWEB        CODSECAO  NUMBER(10,0)          Codigo da Secao    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIAWEB    CODCATEGORIA  NUMBER(10,0)      Codigo da Categoria    CHAVE PRIMÁRIA (PK)                        NaN
PCSUBCATEGORIAWEB     SITUACAOWEB   VARCHAR2(1)                      NaN            OPERACIONAL                        NaN
PCSUBCATEGORIAWEB      DTCADASTRO          DATE         Data de cadastro            OPERACIONAL                        NaN
PCSUBCATEGORIAWEB      DTULTALTER          DATE Data de ultima alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*