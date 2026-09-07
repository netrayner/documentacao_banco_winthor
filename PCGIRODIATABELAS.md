# 📊 Tabela: PCGIRODIATABELAS

### Estrutura de Colunas e Restrições

          Tabela        Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIATABELAS    TIPOTABELA  VARCHAR2(50) Tipo da tabela: Curva, sub-curva ou frequência            OPERACIONAL                        NaN
PCGIRODIATABELAS     DESCRICAO VARCHAR2(100)                            Descrição da tabela            OPERACIONAL                        NaN
PCGIRODIATABELAS         CHAVE  VARCHAR2(30)                             Código do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIATABELAS         ORDEM   NUMBER(6,0)                              Ordem de execução            OPERACIONAL                        NaN
PCGIRODIATABELAS    DTCADASTRO          DATE                               Data de cadastro            OPERACIONAL                        NaN
PCGIRODIATABELAS CODUSUARIOCAD   NUMBER(8,0)                Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIATABELAS   DTALTERACAO          DATE                              Data de alteração            OPERACIONAL                        NaN
PCGIRODIATABELAS CODUSUARIOALT   NUMBER(8,0)                  Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*