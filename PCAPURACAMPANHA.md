# 📊 Tabela: PCAPURACAMPANHA

### Estrutura de Colunas e Restrições

         Tabela          Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPURACAMPANHA       CODFILIAL  VARCHAR2(2)                              Código da filial.            OPERACIONAL                        NaN
PCAPURACAMPANHA        DTINICIO         DATE                    Data de início de vigência.            OPERACIONAL                        NaN
PCAPURACAMPANHA           DTFIM         DATE                        Data final de vigência.            OPERACIONAL                        NaN
PCAPURACAMPANHA   CODSUPERVISOR  NUMBER(4,0)                          Código do supervisor.            OPERACIONAL                        NaN
PCAPURACAMPANHA         CODUSUR  NUMBER(4,0)                                 Código de RCA.            OPERACIONAL                        NaN
PCAPURACAMPANHA        TIPOMETA  VARCHAR2(2)                                  Tipo de meta.            OPERACIONAL                        NaN
PCAPURACAMPANHA          COLUNA VARCHAR2(32)                    Nome da coluna de critério.            OPERACIONAL                        NaN
PCAPURACAMPANHA          CODIGO  NUMBER(8,0)                      Código do item analisado.            OPERACIONAL                        NaN
PCAPURACAMPANHA      TIPOPREMIO  VARCHAR2(2)                             Tipo de premiação.            OPERACIONAL                        NaN
PCAPURACAMPANHA        PREVISTO NUMBER(20,8)                      Valor previsto para meta.            OPERACIONAL                        NaN
PCAPURACAMPANHA       REALIZADO NUMBER(20,8)                      Valor realizado pelo RCA.            OPERACIONAL                        NaN
PCAPURACAMPANHA          PREMIO NUMBER(14,2)                               Valor do Prêmio.            OPERACIONAL                        NaN
PCAPURACAMPANHA      VALEGERADO  VARCHAR2(1)                     Indica se foi gerado vale.            OPERACIONAL                        NaN
PCAPURACAMPANHA          NUMDOC NUMBER(12,0)                   Número do documento de vale.            OPERACIONAL                        NaN
PCAPURACAMPANHA    DATAAPURACAO         DATE                  Data de apuração da campanha.            OPERACIONAL                        NaN
PCAPURACAMPANHA CODFUNCAPURACAO  NUMBER(8,0) Código do funcionário que realizou a apuração.            OPERACIONAL                        NaN
PCAPURACAMPANHA         CODIGO2  NUMBER(8,0)                    Código do item 2 analisado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*