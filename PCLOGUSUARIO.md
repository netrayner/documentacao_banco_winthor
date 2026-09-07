# 📊 Tabela: PCLOGUSUARIO

### Estrutura de Colunas e Restrições

      Tabela               Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGUSUARIO            CODIGOLOG        NUMBER                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGUSUARIO          NOMEUSUARIO  VARCHAR2(40)                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO        DATAHORALOGON          DATE                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO       DATAHORALOGOFF          DATE                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO          NOMEMAQUINA VARCHAR2(255)                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO         SUCESSOLOGON       CHAR(1)                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO MOTIVOINSUCESSOLOGON VARCHAR2(255)                                 NaN            OPERACIONAL                        NaN
PCLOGUSUARIO             IPORIGEM  VARCHAR2(60) IP de origem da requisição de logon            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*