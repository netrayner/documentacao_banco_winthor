# 📊 Tabela: PCINTEGRACAOWMSSAAS

### Estrutura de Colunas e Restrições

             Tabela                   Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOWMSSAAS                CODFILIAL   VARCHAR2(2)                                             Código da filial            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS            NUMDOCWINTHOR  NUMBER(14,0)                              Número do documento do winthor             OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           TIPODOCWINTHOR  VARCHAR2(20)                                 Tipo de documento do winthor            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS                   NUMCAR   NUMBER(8,0)                                       Numero de carregamento            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS            NUMDOCWMSSAAS  NUMBER(14,0)                        Número de documento integrado no Saas            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS         DTFILAINTEGRACAO          DATE            Data que o documento foi disponibilizado na fila.            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS             DTINTEGRACAO          DATE                               Data de integração no WMS Saas            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           DATADOCWINTHOR          DATE                                 Data do documento no winthor            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           DTFIMSEPARACAO          DATE                                     Data do fim da separação            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           DTCANCELAMENTO          DATE                           Data do cancelamento da integração            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS       LIBERADOINTEGRACAO   VARCHAR2(2)                                      Librado para integração            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           TIPOINTEGRACAO  VARCHAR2(20)                                           Tipo de integração            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS                   CODCLI  NUMBER(12,0)                                            Código do cliente            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS                DTENTREGA          DATE                                 Data da entrega do documento            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS                      OBS VARCHAR2(500)                                         Observação do pedido            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS           TIPOGERACAODOC  VARCHAR2(20) Tipo de geração do documente (COMPLETO, FRACIONADO ou CAIXA)            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS                TOTVOLUME  NUMBER(18,6)                                   Total de volumes separados            OPERACIONAL                        NaN
PCINTEGRACAOWMSSAAS FATURAMENTOCONFIRMADOWMS   VARCHAR2(2)          Indica se o documento teve o faturamento confirmado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*