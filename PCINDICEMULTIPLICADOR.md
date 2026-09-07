# 📊 Tabela: PCINDICEMULTIPLICADOR

### Estrutura de Colunas e Restrições

               Tabela     Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDICEMULTIPLICADOR     CODIGO  NUMBER(6,0)                            CODIGO    CHAVE PRIMÁRIA (PK)                        NaN
PCINDICEMULTIPLICADOR  DESCRICAO VARCHAR2(40)                         DESCRICAO            OPERACIONAL                        NaN
PCINDICEMULTIPLICADOR     INDICE  NUMBER(4,2)                            INDICE            OPERACIONAL                        NaN
PCINDICEMULTIPLICADOR      VALOR NUMBER(18,6)                             VALOR            OPERACIONAL                        NaN
PCINDICEMULTIPLICADOR TIPOINDICE  VARCHAR2(1)                    TIPO DO INDICE            OPERACIONAL                        NaN
PCINDICEMULTIPLICADOR   VALORMIN  NUMBER(6,0) Valor Mínimo Indice Multiplicador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*