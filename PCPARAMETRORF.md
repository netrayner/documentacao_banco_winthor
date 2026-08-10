# 📊 Tabela: PCPARAMETRORF

### Estrutura de Colunas e Restrições

       Tabela    Coluna   Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETRORF      NOME   VARCHAR2(50) Nome do componente em que o Delphi irá fazer a conexão com o banco de dados.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETRORF DESCRICAO  VARCHAR2(100)                                           Resumo da atuação que o campo faz.            OPERACIONAL                        NaN
PCPARAMETRORF CODFILIAL    VARCHAR2(2)                                                      Filial que esta em uso.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETRORF     VALOR  VARCHAR2(100)                                                         Dados do componente.            OPERACIONAL                        NaN
PCPARAMETRORF   VALORES VARCHAR2(2000)                                              Configurações de tela do módulo            OPERACIONAL                        NaN
PCPARAMETRORF      TIPO   VARCHAR2(20)                                                Tipo de variável do parâmetro            OPERACIONAL                        NaN
PCPARAMETRORF    MODULO   VARCHAR2(20)                                                          Módulo do parâmetro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*