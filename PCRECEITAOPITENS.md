# 📊 Tabela: PCRECEITAOPITENS

### Estrutura de Colunas e Restrições

          Tabela        Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECEITAOPITENS         NUMOP NUMBER(10,0)               Código da ordem de produção    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAOPITENS       CODPROD  NUMBER(6,0)               Código do produto produzido    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAOPITENS   QTAPRODUZIR NUMBER(22,6)                Quantidade a ser produzida            OPERACIONAL                        NaN
PCRECEITAOPITENS   QTPRODUZIDO NUMBER(22,6) Quantidade produzido no final do processo            OPERACIONAL                        NaN
PCRECEITAOPITENS    DTCADASTRO         DATE                          Data de cadastro            OPERACIONAL                        NaN
PCRECEITAOPITENS   DTALTERACAO         DATE                         Data de alteração            OPERACIONAL                        NaN
PCRECEITAOPITENS CODUSUARIOINC  NUMBER(8,0)             Código do usuário que incluiu            OPERACIONAL                        NaN
PCRECEITAOPITENS CODUSUARIOALT  NUMBER(8,0)             Código do usuário que alterou            OPERACIONAL                        NaN
PCRECEITAOPITENS CODUSUARIOCAN  NUMBER(8,0)            Código do usuário que cancelou            OPERACIONAL                        NaN
PCRECEITAOPITENS         CICLO  NUMBER(4,0)              Ciclo de produção do produto    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*