# 📊 Tabela: PCTABELACOMPLELGPD

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABELACOMPLELGPD CODTABELACOMPLE  NUMBER(8,0)                         Identificador único    CHAVE PRIMÁRIA (PK)                        NaN
PCTABELACOMPLELGPD       CODTABELA  NUMBER(8,0) Código que referência a tabela PCTABELALGPD CHAVE ESTRANGEIRA (FK)               PCTABELALGPD
PCTABELACOMPLELGPD          TABELA VARCHAR2(40)                     Tabela elegivél ao LGPD            OPERACIONAL                        NaN
PCTABELACOMPLELGPD      CAMPOCHAVE VARCHAR2(40)        Campo que é chave primaria da tabela            OPERACIONAL                        NaN
PCTABELACOMPLELGPD   CAMPOCHAVEPAI VARCHAR2(40)      Campo chave que relaciona a tabela pai            OPERACIONAL                        NaN
PCTABELACOMPLELGPD            HASH VARCHAR2(32)    Hash para garantir a fidelidade do dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*