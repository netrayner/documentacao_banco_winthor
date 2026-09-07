# 📊 Tabela: PCREINFR1070

### Estrutura de Colunas e Restrições

      Tabela                Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR1070                    ID  NUMBER(8,0)                      Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR1070               GRUPOID  NUMBER(8,0)             Identificador do grupo            OPERACIONAL                        NaN
PCREINFR1070          TIPOPROCESSO      CHAR(1)                   Tipo do processo            OPERACIONAL                        NaN
PCREINFR1070           NUMPROCESSO VARCHAR2(20)                 Número do processo            OPERACIONAL                        NaN
PCREINFR1070              INIVALID  VARCHAR2(7)                 Inicio de validade            OPERACIONAL                        NaN
PCREINFR1070              FIMVALID  VARCHAR2(7)                  Final da validade            OPERACIONAL                        NaN
PCREINFR1070               CODVARA VARCHAR2(10)                     Código da vara            OPERACIONAL                        NaN
PCREINFR1070               UFSECAO      CHAR(2)        Unidade federativa da seção            OPERACIONAL                        NaN
PCREINFR1070             CODCIDADE  NUMBER(6,0)                   Código da cidade CHAVE ESTRANGEIRA (FK)                   PCCIDADE
PCREINFR1070   AUTORIAACAOJUDICIAL      CHAR(1)           Autoria da ação judicial            OPERACIONAL                        NaN
PCREINFR1070           INIVALID_PK  VARCHAR2(7)              Inicio de validade PK            OPERACIONAL                        NaN
PCREINFR1070           FIMVALID_PK  VARCHAR2(7)               Final da validade PK            OPERACIONAL                        NaN
PCREINFR1070 DTSOLICITACAOEXCLUSAO         DATE    Data de solicitação de exclusão            OPERACIONAL                        NaN
PCREINFR1070            DTEXCLUSAO         DATE                   Data de exclusão            OPERACIONAL                        NaN
PCREINFR1070       CODFUNCULTALTER  NUMBER(8,0) Código do funcionário de alteração            OPERACIONAL                        NaN
PCREINFR1070            DTULTALTER         DATE           Data da ultima alteração            OPERACIONAL                        NaN
PCREINFR1070             CODFORNEC  NUMBER(8,0)               Código do fornecedor            OPERACIONAL                        NaN
PCREINFR1070          TIPOPARCEIRO  VARCHAR2(1)                   Tipo do parceiro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*