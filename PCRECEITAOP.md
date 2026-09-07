# 📊 Tabela: PCRECEITAOP

### Estrutura de Colunas e Restrições

     Tabela          Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECEITAOP           NUMOP  NUMBER(10,0)                 Código da ordem de produção    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAOP       CODFILIAL   VARCHAR2(2)                            Código da filial            OPERACIONAL                        NaN
PCRECEITAOP   DTAGENDAMENTO          DATE                         Data de agendamento            OPERACIONAL                        NaN
PCRECEITAOP DTINICIALIZACAO          DATE     Data inicilaização da ordem de produção            OPERACIONAL                        NaN
PCRECEITAOP   DTFINALIZACAO          DATE       Data finalização da ordem de produção            OPERACIONAL                        NaN
PCRECEITAOP     DTCANCELADO          DATE                        Data de cancelamento            OPERACIONAL                        NaN
PCRECEITAOP MOTIVOCANCELADO VARCHAR2(500) Motivo do cancelamento da ordem de produção            OPERACIONAL                        NaN
PCRECEITAOP      DTCADASTRO          DATE                            Data de cadastro            OPERACIONAL                        NaN
PCRECEITAOP     DTALTERACAO          DATE                           Data de alteração            OPERACIONAL                        NaN
PCRECEITAOP   CODUSUARIOINC   NUMBER(8,0)               Código do usuário que incluiu            OPERACIONAL                        NaN
PCRECEITAOP   CODUSUARIOALT   NUMBER(8,0)               Código do usuário que alterou            OPERACIONAL                        NaN
PCRECEITAOP   CODUSUARIOCAN   NUMBER(8,0)              Código do usuário que cancelou            OPERACIONAL                        NaN
PCRECEITAOP     QTPRODUZIDO  NUMBER(22,6)                        Quantidade produzido            OPERACIONAL                        NaN
PCRECEITAOP   CODUSUARIOEST   NUMBER(8,0)    Código do usuário que estorno a produção            OPERACIONAL                        NaN
PCRECEITAOP     DTESTORNADO          DATE                 Data de estorno da produção            OPERACIONAL                        NaN
PCRECEITAOP   MOTIVOESTORNO VARCHAR2(500)               Motivo do estorno da produção            OPERACIONAL                        NaN
PCRECEITAOP     NUMOPORIGEM  NUMBER(10,0)    Código do usuário que estorno a produção            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*