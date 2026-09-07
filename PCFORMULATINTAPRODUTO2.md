# 📊 Tabela: PCFORMULATINTAPRODUTO2

### Estrutura de Colunas e Restrições

                Tabela         Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULATINTAPRODUTO2     CODMAQUINA  NUMBER(4,0)                                                    CODIGO DA MAQUINA DE TINTA    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTAPRODUTO2 CHAVEPRINCIPAL VARCHAR2(40)                                                     CHAVE DA FORMULA DE TINTA    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTAPRODUTO2       TIPOLATA  VARCHAR2(2) TIPO DA LATA QUE PERTENCE ESTE CODIGO PRODUTO WINTHOR (QUARTO, GALAO OU LATA)    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTAPRODUTO2 CODPRODWINTHOR  NUMBER(6,0)                                 CODIGO DO PRODUTO WINTHOR VINCULADO A FORMULA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*