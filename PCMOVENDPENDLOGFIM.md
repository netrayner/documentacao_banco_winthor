# 📊 Tabela: PCMOVENDPENDLOGFIM

### Estrutura de Colunas e Restrições

            Tabela          Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVENDPENDLOGFIM           NUMOS  NUMBER(10,0)                         Número OS.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVENDPENDLOGFIM         EXESSAO  VARCHAR2(20)                      Tipo do Erro.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM       DESCRICAO VARCHAR2(300)                 Descrlção do Erro.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVENDPENDLOGFIM            DATA          DATE                     Data ocorrida.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM      DATAULTIMA          DATE           Ultima da de ocorrência.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM TOTALOCORRENCIA   NUMBER(8,0)               Total de ocorrência.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM       MATRICULA   NUMBER(8,0)       matricula do usuário logado.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM       CODROTINA   NUMBER(6,0) Codigo da rotina que gerou o erro.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM  USUARIOSISTEMA  VARCHAR2(30)                Usuário do sistema.            OPERACIONAL                        NaN
PCMOVENDPENDLOGFIM         MAQUINA  VARCHAR2(30)           Maquina que gerou o log.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*