# 📊 Tabela: PCINTEGRACAOGESTAORECURSO

### Estrutura de Colunas e Restrições

                   Tabela          Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOGESTAORECURSO              ID  NUMBER(25,0)                                            Id da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOGESTAORECURSO     DATAINICIAL          DATE                     Data inicial da execução do recurso.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO   IDGESTAOFLUXO  NUMBER(19,0) Chave estrangeira para a tabela PCINTEGRACAOGESTAOFLUXO. CHAVE ESTRANGEIRA (FK)    PCINTEGRACAOGESTAOFLUXO
PCINTEGRACAOGESTAORECURSO       DATAFINAL          DATE                       Data final da execução do recurso.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO  STATUSEXECUCAO   NUMBER(1,0)                           Status da execução do recurso.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO   IDROTASERVICO  NUMBER(10,0)                         Id da rota referente ao recurso.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO     NOMERECURSO VARCHAR2(100)                Nome do recurso que está sendo executado.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO QUANTIDADEBUSCA  NUMBER(10,0)                  Quantidade buscada nos plugins de busca            OPERACIONAL                        NaN
PCINTEGRACAOGESTAORECURSO QUANTIDADEENVIO  NUMBER(10,0)                 Quantidade de envio nos plugins de envio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*