# 📊 Tabela: PCPROCESSOANTECIPA

### Estrutura de Colunas e Restrições

            Tabela            Coluna Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROCESSOANTECIPA     NUMTRANSVENDA NUMBER(10,0) Número de transação de venda vinculado ao titulo a receber que esta sendo processado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA             PREST  VARCHAR2(2)                    Número da prestação do título a receber que esta sendo processado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA NUMTRANSVENDAORIG NUMBER(10,0)                                 Número de transação de venda que originou o processo            OPERACIONAL                        NaN
PCPROCESSOANTECIPA         PRESTORIG  VARCHAR2(2)                      Número da prestação do título a receber que originou o processo            OPERACIONAL                        NaN
PCPROCESSOANTECIPA      DATAPROCESSO TIMESTAMP(6)                                             Data e hora que foi realizado o processo            OPERACIONAL                        NaN
PCPROCESSOANTECIPA            ROTINA  VARCHAR2(5)                                                Rotina do WTA que realizou o processo            OPERACIONAL                        NaN
PCPROCESSOANTECIPA            STATUS VARCHAR2(15)                                            Status do processo Aguardando e Executado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA          OPERACAO  VARCHAR2(2)                           Código da operação de integração que esta sendo processado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA     VALORANTECIPA NUMBER(12,2)                                                             Valor que foi antecipado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA      DATAANTECIPA         DATE                                                       Data e hora que foi antecipado            OPERACIONAL                        NaN
PCPROCESSOANTECIPA        IDANTECIPA VARCHAR2(14)                              Identificador do titulo que retornou da API do Antecipa            OPERACIONAL                        NaN
PCPROCESSOANTECIPA          PROCESSO VARCHAR2(15)                              Tipo do processamento da integração Manual e Automático            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*