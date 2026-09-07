# 📊 Tabela: PCLOGPRODUTOS

### Estrutura de Colunas e Restrições

       Tabela               Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPRODUTOS              CODUSUR  NUMBER(8,0)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPRODUTOS        DATAALTERACAO         DATE                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPRODUTOS        CAMPOALTERADO VARCHAR2(20)                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPRODUTOS VALORANTERIORDOCAMPO VARCHAR2(80)                                  NaN            OPERACIONAL                        NaN
PCLOGPRODUTOS    VALORATUALDOCAMPO VARCHAR2(80)                                  NaN            OPERACIONAL                        NaN
PCLOGPRODUTOS              CODPROD  NUMBER(6,0) Código do Produto que foi alterado.     CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPRODUTOS           ROTINALANC VARCHAR2(40)      Indica a rotina dos lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*