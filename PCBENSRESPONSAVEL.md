# 📊 Tabela: PCBENSRESPONSAVEL

### Estrutura de Colunas e Restrições

           Tabela             Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENSRESPONSAVEL     CODRESPONSAVEL  NUMBER(8,0)            Indica o código da responsável do bem.    CHAVE PRIMÁRIA (PK)                        NaN
PCBENSRESPONSAVEL    DESCRESPONSAVEL VARCHAR2(60)         Indica a descrição da responsável do bem.            OPERACIONAL                        NaN
PCBENSRESPONSAVEL     CODLOCALIZACAO  NUMBER(6,0)                     Código da localização do bem.            OPERACIONAL                        NaN
PCBENSRESPONSAVEL PERMITEALTERALOCAL  VARCHAR2(1) Permite alterar localização do bem no lançamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*