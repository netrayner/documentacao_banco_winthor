# 📊 Tabela: PCLOGFATURAMENTO

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGFATURAMENTO              CODLOG  NUMBER(10,0)                                                         Código do registro da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGFATURAMENTO            DATAHORA          DATE                                                                   Data / hora do log            OPERACIONAL                        NaN
PCLOGFATURAMENTO           CODFILIAL   VARCHAR2(2)                                                                     Código da filial            OPERACIONAL                        NaN
PCLOGFATURAMENTO            PROCESSO  VARCHAR2(30)                                            Processo identificador do registro de log            OPERACIONAL                        NaN
PCLOGFATURAMENTO             CODFUNC   NUMBER(8,0)                                               Código do usuário responsável pelo log            OPERACIONAL                        NaN
PCLOGFATURAMENTO           DTINICIAL          DATE                                  Data inicial, para processos que utilizam intervalo            OPERACIONAL                        NaN
PCLOGFATURAMENTO             DTFINAL          DATE                                    Data final, para processos que utilizam intervalo            OPERACIONAL                        NaN
PCLOGFATURAMENTO             MAQUINA VARCHAR2(100)                                         Maquina onde o log do processo foi capturado            OPERACIONAL                        NaN
PCLOGFATURAMENTO            TERMINAL VARCHAR2(100)                                        Terminal onde o log do processo foi capturado            OPERACIONAL                        NaN
PCLOGFATURAMENTO              OSUSER VARCHAR2(100)                                                       Usuario do sistema operacional            OPERACIONAL                        NaN
PCLOGFATURAMENTO CODIGOIDENTIFICADOR  NUMBER(10,0) Codigo identificador do log, usado para encontrar log especifico (ex: numtransvenda)            OPERACIONAL                        NaN
PCLOGFATURAMENTO                 LOG          CLOB                                                              Arquivo ou pilha de log            OPERACIONAL                        NaN
PCLOGFATURAMENTO             TIPOLOG  VARCHAR2(10)                                  Identifica o tipo do log (ERROR, INFO, DEBUG, WARN)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*