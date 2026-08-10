# 📊 Tabela: PCLAYOUTBOLEPIX

### Estrutura de Colunas e Restrições

         Tabela         Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTBOLEPIX         CODIGO NUMBER(10,0)                         Chave primária     CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTBOLEPIX          BANCO  NUMBER(4,0)                        Código do Banco             OPERACIONAL                        NaN
PCLAYOUTBOLEPIX         FILIAL  VARCHAR2(2)                        Código de filial            OPERACIONAL                        NaN
PCLAYOUTBOLEPIX    CODMENSAGEM NUMBER(10,0) Chave estrangeira da PCMENSAGENSBOLEPIX CHAVE ESTRANGEIRA (FK)         PCMENSAGENSBOLEPIX
PCLAYOUTBOLEPIX ORDEMNOBOLEPIX  NUMBER(2,0)              Ordem do layout no bolepix            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*