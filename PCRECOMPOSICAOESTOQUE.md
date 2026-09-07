# 📊 Tabela: PCRECOMPOSICAOESTOQUE

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                                                                                                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECOMPOSICAOESTOQUE      CODFILIAL  VARCHAR2(2)                                                                                                                                                                                             Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCRECOMPOSICAOESTOQUE     TIPOEVENTO  VARCHAR2(2) Tipo de Evento que definirá os dias que serão utilizados para calcular o estoque mínimo ou máximo de um produto. (SB)Sub-Categoria, (CA)Categoria, (SE)Seção, (DE)Departamento, (SC)Sub-Classe ou (C)Classe.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECOMPOSICAOESTOQUE      CODEVENTO  VARCHAR2(6)                                                                                                                                                                           Código referente ao tipo de evento    CHAVE PRIMÁRIA (PK)                        NaN
PCRECOMPOSICAOESTOQUE DIASESTOQUEMIN  NUMBER(3,0)                                                                                                                                   Dias para calcular o estoque mínimo que a empresa deverá manter do produto            OPERACIONAL                        NaN
PCRECOMPOSICAOESTOQUE DIASESTOQUEMAX  NUMBER(3,0)                                                                                                                                   Dias para calcular o estoque máximo que a empresa deverá manter do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*