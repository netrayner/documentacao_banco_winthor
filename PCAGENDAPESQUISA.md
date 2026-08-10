# 📊 Tabela: PCAGENDAPESQUISA

### Estrutura de Colunas e Restrições

          Tabela    Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAPESQUISA CODAGENDA NUMBER(10,0)                                                        Código da Agenda    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAPESQUISA CODFILIAL  VARCHAR2(2)                                                        Código da Filial            OPERACIONAL                        NaN
PCAGENDAPESQUISA NROSEMANA  NUMBER(1,0)                                                    Nro da semana no mês            OPERACIONAL                        NaN
PCAGENDAPESQUISA DIASEMANA  NUMBER(1,0)                                                    Nro do dia da semana            OPERACIONAL                        NaN
PCAGENDAPESQUISA  HRINICIO VARCHAR2(10)                                              Hora de Início da Pesquisa            OPERACIONAL                        NaN
PCAGENDAPESQUISA     HRFIM VARCHAR2(10)                                             Hora de Termino da Pesquisa            OPERACIONAL                        NaN
PCAGENDAPESQUISA   QTMESAS  NUMBER(3,0) Quantidade de mesas a serem pesquisadas no intervalo de hora inicio/fim            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*