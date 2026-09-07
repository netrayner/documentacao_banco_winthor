# 📊 Tabela: PCTRIBVENDAREGIAO

### Estrutura de Colunas e Restrições

           Tabela             Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBVENDAREGIAO CODTRIBVENDAREGIAO  NUMBER(6,0)                  Código de tributação de venda por UF    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBVENDAREGIAO           CODNCMEX VARCHAR2(20)                                         Código NCM+Ex CHAVE ESTRANGEIRA (FK)                      PCNCM
PCTRIBVENDAREGIAO          NUMREGIAO  NUMBER(4,0) Número da regiáo a qual a tributação estara vinculada CHAVE ESTRANGEIRA (FK)                   PCREGIAO
PCTRIBVENDAREGIAO              CODST  NUMBER(4,0)                                          Código do ST CHAVE ESTRANGEIRA (FK)                   PCTRIBUT
PCTRIBVENDAREGIAO   CODTRIBPISCOFINS  NUMBER(4,0)                    Código da tributação do PIS/COFINS CHAVE ESTRANGEIRA (FK)            PCTRIBPISCOFINS
PCTRIBVENDAREGIAO         DTINCLUSAO         DATE                                      Data de Inclusão            OPERACIONAL                        NaN
PCTRIBVENDAREGIAO    CODFUNCINCLUSAO  NUMBER(4,0)                        Código do funcionario inclusão            OPERACIONAL                        NaN
PCTRIBVENDAREGIAO     ROTINAINCLUSAO VARCHAR2(30)                                    Rotina de inclusão            OPERACIONAL                        NaN
PCTRIBVENDAREGIAO           DTULTALT         DATE                              Data de última alteração            OPERACIONAL                        NaN
PCTRIBVENDAREGIAO      CODFUNCULTALT  NUMBER(4,0)                Código do funcionario última alteração            OPERACIONAL                        NaN
PCTRIBVENDAREGIAO       ROTINAULTALT VARCHAR2(30)                            Rotina de última alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*