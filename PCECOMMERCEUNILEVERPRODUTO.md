# 📊 Tabela: PCECOMMERCEUNILEVERPRODUTO

### Estrutura de Colunas e Restrições

                    Tabela     Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEUNILEVERPRODUTO  CODFILIAL  VARCHAR2(2) Código da filial que recebeu o cliente    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCECOMMERCEUNILEVERPRODUTO    CODPROD  NUMBER(6,0)                      Código do produto    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCECOMMERCEUNILEVERPRODUTO DTINCLUSAO         DATE                       Data de cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*