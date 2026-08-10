# 📊 Tabela: PCLOCALINVENTARIO

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOCALINVENTARIO    CODLOCAL VARCHAR2(20)                                                Indica o código do local .    CHAVE PRIMÁRIA (PK)                        NaN
PCLOCALINVENTARIO       LOCAL VARCHAR2(40)                                              Indica o descrição do local.            OPERACIONAL                        NaN
PCLOCALINVENTARIO ESTOQUELOJA  VARCHAR2(1) Define se no inventario por local atualizará ou não o estoque frente loja            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*