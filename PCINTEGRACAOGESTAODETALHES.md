# 📊 Tabela: PCINTEGRACAOGESTAODETALHES

### Estrutura de Colunas e Restrições

                    Tabela          Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOGESTAODETALHES       DATAFINAL         DATE                         Data final da execução do detalhe.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAODETALHES              ID NUMBER(30,0)                                              Id da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOGESTAODETALHES IDGESTAORECURSO NUMBER(25,0) Chave estrangeira para a tabela PCINTEGRACAOGESTAORECURSO. CHAVE ESTRANGEIRA (FK)  PCINTEGRACAOGESTAORECURSO
PCINTEGRACAOGESTAODETALHES     DATAINICIAL         DATE                       Data inicial da execução do detalhe.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAODETALHES  STATUSEXECUCAO  NUMBER(1,0)                             Status da execução do detalhe.            OPERACIONAL                        NaN
PCINTEGRACAOGESTAODETALHES      NOMETHREAD VARCHAR2(60)              Nome da thread que está executando o detalhe;            OPERACIONAL                        NaN
PCINTEGRACAOGESTAODETALHES       DESCRICAO         CLOB                                      Descrição do detalhe;            OPERACIONAL                        NaN
PCINTEGRACAOGESTAODETALHES            ERRO         CLOB         Descrição em caso de falha na execução do detalhe;            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*