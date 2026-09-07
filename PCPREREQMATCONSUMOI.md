# 📊 Tabela: PCPREREQMATCONSUMOI

### Estrutura de Colunas e Restrições

             Tabela              Coluna Tipo/Tamanho                                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPREREQMATCONSUMOI    NUMPREREQUISICAO  NUMBER(8,0)                                  Número da requisição relacionada            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI             CODPROD  NUMBER(6,0)                                                 Código do produto            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI                  QT NUMBER(20,6)                                            Quantidade requisitada            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI             NUMLOTE VARCHAR2(15)                                                    Número do lote            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI             CODOPER  VARCHAR2(2)                                                Código da operação            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI         QTREQORIGEM NUMBER(20,6) Sempre ficará a quantidade que foi requisitada pela primeira vez.            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI       NUMTRANSVENDA NUMBER(10,0)                                              Número de transação.            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI IDINTEGRACAOMYFROTA          RAW                                                               NaN            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI         IDSOFITVIEW VARCHAR2(10)            Indica o código da requisição de material na SofitView            OPERACIONAL                        NaN
PCPREREQMATCONSUMOI         CODDEPOSITO NUMBER(10,0)       Código do depósito onde o estoque esta armazenado na filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*