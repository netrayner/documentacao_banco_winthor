# 📊 Tabela: PCLOGDADOSMDFE

### Estrutura de Colunas e Restrições

        Tabela        Coluna   Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDADOSMDFE          DATA           DATE                                                     Data do log            OPERACIONAL                        NaN
PCLOGDADOSMDFE       CODFUNC    NUMBER(8,0)                                           Código do funcionário            OPERACIONAL                        NaN
PCLOGDADOSMDFE     CODROTINA    NUMBER(6,0)                                                Código da rotina            OPERACIONAL                        NaN
PCLOGDADOSMDFE        COLUNA   VARCHAR2(30)                                                  Nome da coluna            OPERACIONAL                        NaN
PCLOGDADOSMDFE     TIPOVALOR    VARCHAR2(1) Tipo do valor da coluna (N: numerico; A: alfanumerido; D: data)            OPERACIONAL                        NaN
PCLOGDADOSMDFE     VALORNOVO VARCHAR2(2000)                                            Novo valor da coluna            OPERACIONAL                        NaN
PCLOGDADOSMDFE VALORANTERIOR VARCHAR2(2000)                                        Valor anterior da coluna            OPERACIONAL                        NaN
PCLOGDADOSMDFE   OBSERVACOES  VARCHAR2(100)                                   Observações sobre a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE       MAQUINA   VARCHAR2(64)                          Maquina onde foi realizada a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE      PROGRAMA   VARCHAR2(64)                    Programa utilizado para realizar a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE      TERMINAL   VARCHAR2(30)                    Terminal utilizado para realizar a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE        OSUSER   VARCHAR2(30)                                  Usuário do Sistema Operacional            OPERACIONAL                        NaN
PCLOGDADOSMDFE  OBSERVACOES2 VARCHAR2(2000)                                   Observações sobre a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE  OBSERVACOES3  VARCHAR2(100)                                   Observações sobre a alteração            OPERACIONAL                        NaN
PCLOGDADOSMDFE  NUMTRANSACAO   NUMBER(10,0)                                     Número da transação do MDFe            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*