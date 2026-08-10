# 📊 Tabela: PCRECURSOPRODUCAO

### Estrutura de Colunas e Restrições

           Tabela         Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECURSOPRODUCAO      CODFILIAL   VARCHAR2(2)                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCRECURSOPRODUCAO      IDRECURSO  NUMBER(10,0) Identificação (Código) do recurso    CHAVE PRIMÁRIA (PK)                        NaN
PCRECURSOPRODUCAO           TIPO   VARCHAR2(1)   Tipo de Recurso (Máquina/Homem)            OPERACIONAL                        NaN
PCRECURSOPRODUCAO      DESCRICAO  VARCHAR2(40)              Descrição do Recurso            OPERACIONAL                        NaN
PCRECURSOPRODUCAO      CUSTOHORA  NUMBER(18,6)         Custo por hora do recurso            OPERACIONAL                        NaN
PCRECURSOPRODUCAO CAPACIDADEHORA  NUMBER(18,6)   Capacidade Produtiva do Recurso            OPERACIONAL                        NaN
PCRECURSOPRODUCAO       SITUACAO   VARCHAR2(1)     Situação cadastral do recurso            OPERACIONAL                        NaN
PCRECURSOPRODUCAO            OBS VARCHAR2(200)         Observação para o recurso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*