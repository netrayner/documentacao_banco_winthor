# 📊 Tabela: PCCOTAP

### Estrutura de Colunas e Restrições

 Tabela      Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTAP NUMPESQUISA NUMBER(10,0)       Número da pesquisa de cotação.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTAP   CODCONCOR  VARCHAR2(4)  Código do concorrente participante.    CHAVE PRIMÁRIA (PK)                   PCCONCOR
PCCOTAP  DTCADASTRO         DATE                    Data de cadastro.            OPERACIONAL                        NaN
PCCOTAP  CODFUNCCAD  NUMBER(8,0) Código do funcionário que cadastrou.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*