# 📊 Tabela: PCCATALOGOSOLUCAO

### Estrutura de Colunas e Restrições

           Tabela                  Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATALOGOSOLUCAO                      ID  NUMBER(10,0)                Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCATALOGOSOLUCAO               DESCRICAO VARCHAR2(250)   Descrição do catálogo de soluções            OPERACIONAL                        NaN
PCCATALOGOSOLUCAO CATALOGOPENDENCIACODIGO  NUMBER(10,0) Identificador do catálogo de pendência CHAVE ESTRANGEIRA (FK)        PCCATALOGOPENDENCIA
PCCATALOGOSOLUCAO                EDITAVEL   NUMBER(1,0)      Informa se o catálogo é editável            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*