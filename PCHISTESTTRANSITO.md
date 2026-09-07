# 📊 Tabela: PCHISTESTTRANSITO

### Estrutura de Colunas e Restrições

           Tabela         Coluna Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTESTTRANSITO           DATA         DATE                                              Data do histórico    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTTRANSITO      CODFILIAL  VARCHAR2(2)                                               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTTRANSITO        CODPROD  NUMBER(6,0)                                              Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTTRANSITO POSSECODFORNEC  NUMBER(6,0) Código do fornecedor (empresa) que está de posse da mercadoria    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTESTTRANSITO     QTTRANSITO NUMBER(22,8)                       Quantidade em Trânsito definido por CNPJ            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*