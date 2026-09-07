# 📊 Tabela: PCCOMISSAOTERCEIROS

### Estrutura de Colunas e Restrições

             Tabela          Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOTERCEIROS          CODIGO NUMBER(10,0) Indica o código do registro de comissão de terceiros.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOTERCEIROS      DTCADASTRO         DATE                            Indica a data de cadastro.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS CODFUNCCADASTRO  NUMBER(8,0)                   Indica o funcionário que cadastrou.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS      DTULTALTER         DATE                    Indica a data da última alteração.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS    CODFUNCALTER  NUMBER(8,0)        Indica o funcionário que fez última alteração.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS            TIPO  VARCHAR2(4)                            Indica o tipo de comissão.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS    TIPOTERCEIRO  VARCHAR2(1)                            Indica o tipo de terceiro.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS      PRIORIDADE  NUMBER(2,0)                                  Indica a prioridade.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS       CODFILIAL  VARCHAR2(2)                            Indica o código da filial.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS        DTINICIO         DATE                  Indica a data de início de vigência.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS           DTFIM         DATE                      Indica a data final de vigência.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS     CODTERCEIRO  NUMBER(8,0)                          Indica o código de terceiro.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS          CODCLI  NUMBER(6,0)                           Indica o código de cliente.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS         CODEPTO  NUMBER(6,0)                      Indica o código de departamento.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS          CODSEC  NUMBER(6,0)                             Indica o código de seção.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS         CODPROD  NUMBER(6,0)                           Indica o código do produto.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS          PERCOM  NUMBER(8,4)                      Indica o percentual da comissão.            OPERACIONAL                        NaN
PCCOMISSAOTERCEIROS      DTMXSALTER         DATE                                                   NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*