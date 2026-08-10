# 📊 Tabela: PCCIDADEFORNEC

### Estrutura de Colunas e Restrições

        Tabela             Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCIDADEFORNEC       CODMUNICIPIO NUMBER(10,0)                                     Indica o código da cidade.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIDADEFORNEC          CODFORNEC  NUMBER(6,0)                                 Indica o código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIDADEFORNEC CODMUNICIPIOFORNEC VARCHAR2(40) Indica valor que representa relação entra cidade e fornecedor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*