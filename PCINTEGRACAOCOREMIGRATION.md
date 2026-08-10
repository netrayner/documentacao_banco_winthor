# 📊 Tabela: PCINTEGRACAOCOREMIGRATION

### Estrutura de Colunas e Restrições

                   Tabela        Coluna  Tipo/Tamanho                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOCOREMIGRATION          NOME VARCHAR2(255)                                                   Armazena o nome do migration            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION     DTCRIACAO          DATE                                                     Armazena a data de criação            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION DTATUALIZACAO          DATE                                                 Armazena a data de atualização            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION DESCRICAOERRO          CLOB                                                   Armazena a descrição do erro            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION       SUCESSO   VARCHAR2(1) Armazena o valor S para caso a integração seja SUCESSO e N para caso haja erro            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION    TENTATIVAS  NUMBER(10,0)                                                       Quantidade de tentativas            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION         TESTE   VARCHAR2(1)                     Armazena o valor S caso ambiente teste ou N caso contrário            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION     SQLGERADO          CLOB            Armazena o sql ou bloco anônimo com os inserts ou updates do layout            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION        VERSAO  VARCHAR2(10)                                                               Versão do layout            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION   PROJETONOME  VARCHAR2(20)                                                                 Nome do layout            OPERACIONAL                        NaN
PCINTEGRACAOCOREMIGRATION        TABELA  VARCHAR2(40)                                                       Nome da tabela do layout            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*