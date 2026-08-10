# 📊 Tabela: PCCATALOGOSOLUCAO

### Estrutura de Colunas e Restrições

           Tabela                  Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCATALOGOSOLUCAO                      ID  NUMBER(10,0)                Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCATALOGOSOLUCAO               DESCRICAO VARCHAR2(250)   DescriÃ§Ã£o do catÃ¡logo de soluÃ§Ãµes            OPERACIONAL                        NaN
PCCATALOGOSOLUCAO CATALOGOPENDENCIACODIGO  NUMBER(10,0) Identificador do catÃ¡logo de pendÃªncia CHAVE ESTRANGEIRA (FK)        PCCATALOGOPENDENCIA
PCCATALOGOSOLUCAO                EDITAVEL   NUMBER(1,0)      Informa se o catÃ¡logo Ã© editÃ¡vel            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*