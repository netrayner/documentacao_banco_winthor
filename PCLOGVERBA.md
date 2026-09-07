# 📊 Tabela: PCLOGVERBA

### Estrutura de Colunas e Restrições

    Tabela         Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGVERBA         CODIGO       NUMBER                              Grava o sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGVERBA      CODFILIAL  VARCHAR2(2)                                          Código da filial            OPERACIONAL                        NaN
PCLOGVERBA         TABELA VARCHAR2(30)                               Tabela que sofreu alteração            OPERACIONAL                        NaN
PCLOGVERBA       NUMVERBA  NUMBER(8,0)                               Número da verba movimentada            OPERACIONAL                        NaN
PCLOGVERBA OBJETOALTERADO         CLOB         Grava os dados da tabela alterada em formato JSON            OPERACIONAL                        NaN
PCLOGVERBA   DATAINCLUSAO         DATE                              Data de inclusão do registro            OPERACIONAL                        NaN
PCLOGVERBA        MAQUINA VARCHAR2(64)                          Máquina que executou a alteração            OPERACIONAL                        NaN
PCLOGVERBA         ROTINA VARCHAR2(64)                           Rotina que executou a alteração            OPERACIONAL                        NaN
PCLOGVERBA        USUARIO VARCHAR2(30)                          Usuário que executou a alteração            OPERACIONAL                        NaN
PCLOGVERBA       SITUACAO VARCHAR2(20) Tipo de comando executado (INCLUSAO, EXCLUSAO, ALTERACAO)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*