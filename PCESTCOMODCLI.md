# 📊 Tabela: PCESTCOMODCLI

### Estrutura de Colunas e Restrições

       Tabela    Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTCOMODCLI CODFILIAL  VARCHAR2(2)                         Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCOMODCLI    CODCLI  NUMBER(6,0)               Código do Cliente Comodato    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCOMODCLI   CODPROD  NUMBER(6,0)             Código do Produto Comodatado    CHAVE PRIMÁRIA (PK)                        NaN
PCESTCOMODCLI  QTESTGER NUMBER(22,8) Estoque do Produto Comodatado no Cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*