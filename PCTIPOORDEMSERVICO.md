# 📊 Tabela: PCTIPOORDEMSERVICO

### Estrutura de Colunas e Restrições

            Tabela                  Coluna Tipo/Tamanho                                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOORDEMSERVICO                 CODTIPO  NUMBER(6,0)                                                         Indica o código do típo da ordem de serviço.    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOORDEMSERVICO               DESCRICAO VARCHAR2(40)                                                              Indica a descrição da ordem de serviço.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO GERARCONTRECEBERSERVICO  VARCHAR2(1)                                                           Gerar contas a receber Serviços prestados.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO GERARCONTRECEBERPRODUTO  VARCHAR2(1)                                                          Gerar contas a receber produtos utilizados.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO     PARTICIPANTECLIENTE  VARCHAR2(1)                                                                                Participante cliente.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO         PARTICIPANTERCA  VARCHAR2(1)                                                                                    Participante RCA.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO  PARTICIPANTESUPERVISOR  VARCHAR2(1)                                                                             Participante supervisor.            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO              OSCOMODATO  VARCHAR2(1)                        Campo para definir se o tipo de serviço é de uma ordem de serviço de comodato            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO      PERMITEFATOSABERTA  VARCHAR2(1)         Campo para definir se é permitido Faturar Ordens de serviços que estão com o status ¿Aberta¿            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO      GERAREMESSCOMODATO  VARCHAR2(1) Campo para definir que ao faturar a Ordem de serviço deve ser gerada uma nota de remessa de comodato            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO          ALTERASTATUSOS  VARCHAR2(1)                                                Alterar automaticamente o status da OS no faturamento            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO        PARTICIPANTEFUNC  VARCHAR2(1)                                                                          Participante de funcionario            OPERACIONAL                        NaN
PCTIPOORDEMSERVICO            GERARNOTATV1  VARCHAR2(1)                                                                                Gerar nota fiscal TV1            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*