# 📊 Tabela: PCOCORRENCIARF

### Estrutura de Colunas e Restrições

        Tabela      Coluna   Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOCORRENCIARF        DATA           DATE                                                                Data do lançamento da ocorrência pelao usuário.            OPERACIONAL                        NaN
PCOCORRENCIARF   CODMOTIVO    NUMBER(4,0)                                          Código do motivo da ocorrência que deve estar cadastrada na PCTABDEV.            OPERACIONAL                        NaN
PCOCORRENCIARF   DOCUMENTO   NUMBER(20,0)                                                                             Número do documento da ocorrência.            OPERACIONAL                        NaN
PCOCORRENCIARF CODFUNCLANC    NUMBER(8,0)                                                             Código do funcionário que deu origem a ocorrência.            OPERACIONAL                        NaN
PCOCORRENCIARF  CODFUNCAUD    NUMBER(8,0)                                                 Código do funcionário que irá fazer a auditoria na ocorrência.            OPERACIONAL                        NaN
PCOCORRENCIARF     TIPODOC    VARCHAR2(2) Tipo do documento da ocorrência [P] pedido, [C] carregamento, [OS] ordem serviço e [OE] ordem serviço entrada.            OPERACIONAL                        NaN
PCOCORRENCIARF     CODPROD    NUMBER(6,0)                                                             Código do produto em que foi lançada a ocorrência.            OPERACIONAL                        NaN
PCOCORRENCIARF        ACAO VARCHAR2(2000)                                                      Ação que o funcionário que realizou a auditoria executou.            OPERACIONAL                        NaN
PCOCORRENCIARF     DATAAUD           DATE                                                                               Data da realização da auditoria.            OPERACIONAL                        NaN
PCOCORRENCIARF     RUACONF    NUMBER(6,0)                                                                                        A rua que foi conferida            OPERACIONAL                        NaN
PCOCORRENCIARF    ACAOAUDI  VARCHAR2(200)                                                                                        Ação de auditoria do RF            OPERACIONAL                        NaN
PCOCORRENCIARF  ROTINALANC   VARCHAR2(80)                                                                                 Rotina que lançou a ocorrencia            OPERACIONAL                        NaN
PCOCORRENCIARF      CODSEP    NUMBER(8,0)                                                                                                      Separador            OPERACIONAL                        NaN
PCOCORRENCIARF      TIPOOS    NUMBER(2,0)                                                                                                     Tipo da OS            OPERACIONAL                        NaN
PCOCORRENCIARF    OPERACAO   VARCHAR2(15)                                                                          Operação  onde ocorreu  a ocorrênciia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*