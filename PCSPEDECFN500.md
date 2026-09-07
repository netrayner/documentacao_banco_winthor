# 📊 Tabela: PCSPEDECFN500

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFN500           ID NUMBER(22,0)          Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFN500 IDLANCAMENTO       NUMBER              ID da tabela PCSPEDECFLANCAMENTO CHAVE ESTRANGEIRA (FK)        PCSPEDECFLANCAMENTO
PCSPEDECFN500        VALOR NUMBER(22,4)                           Valor do lançamento            OPERACIONAL                        NaN
PCSPEDECFN500    DTCRIACAO         DATE Data de criação do registro no banco de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*