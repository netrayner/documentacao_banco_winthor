# 📊 Tabela: PCSPEDECFN600

### Estrutura de Colunas e Restrições

       Tabela       Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFN600           ID NUMBER(22,0)          Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFN600 IDLANCAMENTO       NUMBER              ID da tabela PCSPEDECFLANCAMENTO CHAVE ESTRANGEIRA (FK)        PCSPEDECFLANCAMENTO
PCSPEDECFN600        VALOR NUMBER(22,4)                           Valor do lançamento            OPERACIONAL                        NaN
PCSPEDECFN600    DTCRIACAO         DATE Data de criação do registro no banco de dados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*