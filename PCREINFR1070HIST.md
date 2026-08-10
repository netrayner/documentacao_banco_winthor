# 📊 Tabela: PCREINFR1070HIST

### Estrutura de Colunas e Restrições

          Tabela          Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR1070HIST              ID  NUMBER(8,0)                             Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR1070HIST        R1070_ID  NUMBER(8,0)           Identificador do registro R1070            OPERACIONAL                        NaN
PCREINFR1070HIST        INIVALID  VARCHAR2(7)                        Inicio da validade            OPERACIONAL                        NaN
PCREINFR1070HIST        FIMVALID  VARCHAR2(7)                         Final da validade            OPERACIONAL                        NaN
PCREINFR1070HIST    HASHCADASTRO     CHAR(32)                   Código HASH do cadastro            OPERACIONAL                        NaN
PCREINFR1070HIST    HASHVALIDADE     CHAR(32)                   Código HASH de validade            OPERACIONAL                        NaN
PCREINFR1070HIST      DTEXCLUSAO         DATE                          Data de exclusão            OPERACIONAL                        NaN
PCREINFR1070HIST   DTTRANSMISSAO         DATE                       Data de transmissão            OPERACIONAL                        NaN
PCREINFR1070HIST TIPOTRANSMISSAO VARCHAR2(50)                       Tipo de transmissão            OPERACIONAL                        NaN
PCREINFR1070HIST CODFUNCULTALTER  NUMBER(8,0) Codigo do funcionario da ultima alteração            OPERACIONAL                        NaN
PCREINFR1070HIST      DTULTALTER         DATE                  Data da ultima alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*