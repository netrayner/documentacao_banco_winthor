# 📊 Tabela: PCGIRODIAPESO

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIAPESO    CODPERIODO  NUMBER(6,0)               Código do período    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAPESO          ITEM  NUMBER(6,0)                  Número do item    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAPESO          PESO NUMBER(18,6)                   Valor do peso            OPERACIONAL                        NaN
PCGIRODIAPESO    DTCADASTRO         DATE                Data de cadastro            OPERACIONAL                        NaN
PCGIRODIAPESO CODUSUARIOCAD  NUMBER(8,0) Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIAPESO   DTALTERACAO         DATE               Data de alteração            OPERACIONAL                        NaN
PCGIRODIAPESO CODUSUARIOALT  NUMBER(8,0)   Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*