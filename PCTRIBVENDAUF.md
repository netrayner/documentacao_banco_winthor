# 📊 Tabela: PCTRIBVENDAUF

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBVENDAUF   CODTRIBVENDAUF  NUMBER(6,0)   Código de tributação de venda por UF    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBVENDAUF         CODNCMEX VARCHAR2(20)                          Código NCM+Ex CHAVE ESTRANGEIRA (FK)                      PCNCM
PCTRIBVENDAUF        CODFILIAL  VARCHAR2(2)             Código da filial de origem CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCTRIBVENDAUF        UFDESTINO  VARCHAR2(2)                      Estado de destino CHAVE ESTRANGEIRA (FK)                   PCESTADO
PCTRIBVENDAUF            CODST  NUMBER(4,0)                           Código do ST CHAVE ESTRANGEIRA (FK)                   PCTRIBUT
PCTRIBVENDAUF CODTRIBPISCOFINS  NUMBER(4,0)     Código da tributação do PIS/COFINS CHAVE ESTRANGEIRA (FK)            PCTRIBPISCOFINS
PCTRIBVENDAUF       DTINCLUSAO         DATE                       Data de Inclusão            OPERACIONAL                        NaN
PCTRIBVENDAUF  CODFUNCINCLUSAO  NUMBER(4,0)         Código do funcionario inclusão            OPERACIONAL                        NaN
PCTRIBVENDAUF   ROTINAINCLUSAO VARCHAR2(30)                     Rotina de inclusão            OPERACIONAL                        NaN
PCTRIBVENDAUF         DTULTALT         DATE               Data de última alteração            OPERACIONAL                        NaN
PCTRIBVENDAUF    CODFUNCULTALT  NUMBER(4,0) Código do funcionario última alteração            OPERACIONAL                        NaN
PCTRIBVENDAUF     ROTINAULTALT VARCHAR2(30)             Rotina de última alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*