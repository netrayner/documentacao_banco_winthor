# 📊 Tabela: PCLOG_RECALCULOPROD

### Estrutura de Colunas e Restrições

             Tabela        Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOG_RECALCULOPROD     CODFILIAL  VARCHAR2(2)                               Código da filial para recalculo            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD       CODPROD  NUMBER(6,0)                           Código do produto a ser recalculado            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD         DTLOG         DATE                 Data da inserção do registro na tabela de log            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD   DTRECALCULO         DATE                 Data em que o registro foi incluído na tabela            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD    DTINCLUSAO         DATE Data em que o registro foi incluido na tabela PCRECALCULOPROD            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD NUMTRANSVENDA NUMBER(10,0)                                  Número da transação de venda            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD            QT NUMBER(20,6)                                            Quantidade do item            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD  TIPOREGISTRO  VARCHAR2(1)                                     Tipo de registro de venda            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD ATUALIZADO507  VARCHAR2(1)              Indica se o registro já foi recalculado pela 507            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD      DTDELETE         DATE         Data da remoção do registro da tabela PCRECALCULOPROD            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD      PROGRAMA VARCHAR2(64)                             Aplicação que executou a operação            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD       MAQUINA VARCHAR2(64)                               Estação que executou a operação            OPERACIONAL                        NaN
PCLOG_RECALCULOPROD       USUARIO VARCHAR2(64)                               Usuário que executou a operação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*