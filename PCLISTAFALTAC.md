# 📊 Tabela: PCLISTAFALTAC

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLISTAFALTAC        NUMLISTA  NUMBER(6,0)   Numero da lista de compras    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAFALTAC       CODFILIAL  VARCHAR2(2)             Código da filial            OPERACIONAL                        NaN
PCLISTAFALTAC           LISTA VARCHAR2(40)                Nome da lista            OPERACIONAL                        NaN
PCLISTAFALTAC CODFUNCCADASTRO  NUMBER(6,0)        Código do funcionário            OPERACIONAL                        NaN
PCLISTAFALTAC      DTCADASTRO         DATE             Data do cadastro            OPERACIONAL                        NaN
PCLISTAFALTAC          STATUS  VARCHAR2(1) Data de exclusao do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*