# 📊 Tabela: PCESTTRANSITO

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTTRANSITO      CODFILIAL  VARCHAR2(2)                                             Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTTRANSITO        CODPROD  NUMBER(6,0)                                            Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCESTTRANSITO POSSECODFORNEC  NUMBER(6,0) Código fornecedor da empresa que está de posse da mercadoria    CHAVE PRIMÁRIA (PK)                        NaN
PCESTTRANSITO     QTTRANSITO NUMBER(22,8)                 Qtde. que está sob a posse desse fornecedor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*