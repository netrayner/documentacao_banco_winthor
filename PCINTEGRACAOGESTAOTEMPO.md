# 📊 Tabela: PCINTEGRACAOGESTAOTEMPO

### Estrutura de Colunas e Restrições

                 Tabela          Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOGESTAOTEMPO              ID NUMBER(30,0)                                              Id da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCINTEGRACAOGESTAOTEMPO IDGESTAORECURSO NUMBER(25,0) Chave estrangeira para a tabela PCINTEGRACAOGESTAORECURSO CHAVE ESTRANGEIRA (FK)  PCINTEGRACAOGESTAORECURSO
PCINTEGRACAOGESTAOTEMPO  TEMPODECORRIDO NUMBER(10,0)       Tempo em milissegundos de determinado processamento            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOTEMPO       DESCRICAO         CLOB                                Descrição do processamento            OPERACIONAL                        NaN
PCINTEGRACAOGESTAOTEMPO      NOMETHREAD VARCHAR2(60)        Nome da thread que está executando o processamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*