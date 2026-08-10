# 📊 Tabela: PCSYSTAXLOGALT

### Estrutura de Colunas e Restrições

        Tabela              Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSYSTAXLOGALT                DATA         DATE                                       Data e hora da inclusão do log.            OPERACIONAL                        NaN
PCSYSTAXLOGALT                  ID NUMBER(20,0)                                             Identificação do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCSYSTAXLOGALT             CODPROD  NUMBER(6,0)                                                     Código do Produto            OPERACIONAL                        NaN
PCSYSTAXLOGALT           CODFIGURA  NUMBER(8,0)                                        Código da Figura de tributação            OPERACIONAL                        NaN
PCSYSTAXLOGALT              ORIGEM VARCHAR2(30)                             Identificação da origem do log registrado            OPERACIONAL                        NaN
PCSYSTAXLOGALT          CODCENARIO VARCHAR2(12)                                Código do cenário da tributação Systax            OPERACIONAL                        NaN
PCSYSTAXLOGALT                 NCM VARCHAR2(15)                                                         Código do Ncm            OPERACIONAL                        NaN
PCSYSTAXLOGALT           SITTRIBUT  VARCHAR2(3)                                                   Situação tributária            OPERACIONAL                        NaN
PCSYSTAXLOGALT           CODFILIAL  VARCHAR2(3)                                      Código da filial geradora do log            OPERACIONAL                        NaN
PCSYSTAXLOGALT          PERCICMRED NUMBER(12,4)                                         Percentual de redução do Icms            OPERACIONAL                        NaN
PCSYSTAXLOGALT    PERCICMSDIFERIDO NUMBER(18,4)                                           Percentual diferido do icms            OPERACIONAL                        NaN
PCSYSTAXLOGALT              PERICM NUMBER(18,4)                                                    Percentual do icms            OPERACIONAL                        NaN
PCSYSTAXLOGALT PERCICMSDESONERACAO NUMBER(18,4)                                           Percentual icms desoneração            OPERACIONAL                        NaN
PCSYSTAXLOGALT          PERCFUNCEP NUMBER(18,4)                                                     Percentual funcep            OPERACIONAL                        NaN
PCSYSTAXLOGALT         VLPAUTAICMS NUMBER(18,4)                                                      Valor Pauta ICMS            OPERACIONAL                        NaN
PCSYSTAXLOGALT    PERCDIFALIQUOTAS NUMBER(18,4)                                    Percentual Diferencial de aliquota            OPERACIONAL                        NaN
PCSYSTAXLOGALT          REDBASEIVA NUMBER(18,4)                                                      Redução base Iva            OPERACIONAL                        NaN
PCSYSTAXLOGALT         PERCALIQINT NUMBER(18,4)                                           Percentual aliquota interna            OPERACIONAL                        NaN
PCSYSTAXLOGALT            PERCFECP NUMBER(18,4)                                                       Percentual Fecp            OPERACIONAL                        NaN
PCSYSTAXLOGALT         PERCMVAORIG NUMBER(18,4)                                                   Percentual Mva Orig            OPERACIONAL                        NaN
PCSYSTAXLOGALT             PERCIVA NUMBER(18,4)                                                        Percentual Iva            OPERACIONAL                        NaN
PCSYSTAXLOGALT             VLPAUTA NUMBER(18,4)                                                           Valor Pauta            OPERACIONAL                        NaN
PCSYSTAXLOGALT   PERCIVAICMANTECIP NUMBER(18,4)                                         Percentual Iva Icm Antecipado            OPERACIONAL                        NaN
PCSYSTAXLOGALT    VLPAUTAICMSANTEC NUMBER(18,4)                                           Valor pauta icms antecipado            OPERACIONAL                        NaN
PCSYSTAXLOGALT   PERICMSANTECIPADO NUMBER(18,4)                                            Percentual icms antecipado            OPERACIONAL                        NaN
PCSYSTAXLOGALT     PISCOFINSRETIDO  VARCHAR2(1) Identificador do produto é retido ou não para o processo do PisCofins            OPERACIONAL                        NaN
PCSYSTAXLOGALT CODSITTRIBPISCOFINS  NUMBER(3,0)                    Código da situação tributária do pis e cofins. Cst            OPERACIONAL                        NaN
PCSYSTAXLOGALT              PERPIS NUMBER(12,4)                                                     Percentual do pis            OPERACIONAL                        NaN
PCSYSTAXLOGALT           PERCOFINS NUMBER(12,4)                                                  Percentual do Cofins            OPERACIONAL                        NaN
PCSYSTAXLOGALT              EXTIPI  VARCHAR2(6)                                                       Registro do Ipi            OPERACIONAL                        NaN
PCSYSTAXLOGALT             PERCIPI NUMBER(12,4)                                                     Percentual do IPI            OPERACIONAL                        NaN
PCSYSTAXLOGALT          VLPAUTAIPI NUMBER(18,4)                                                    Valor da Pauta IPI            OPERACIONAL                        NaN
PCSYSTAXLOGALT         CALCCREDIPI  VARCHAR2(1)                                                   Calcula crédito IPI            OPERACIONAL                        NaN
PCSYSTAXLOGALT             IDTRANS NUMBER(10,0)                          Identificação da transação do log registrado            OPERACIONAL                        NaN
PCSYSTAXLOGALT           MATRICULA  NUMBER(8,0)                          Identificação da matricula registrada no Log            OPERACIONAL                        NaN
PCSYSTAXLOGALT             MAQUINA VARCHAR2(64)         Identificação da máquina utilizada no processo de atualização            OPERACIONAL                        NaN
PCSYSTAXLOGALT             USUARIO VARCHAR2(64)                                    Identificação do usuário do banco.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*