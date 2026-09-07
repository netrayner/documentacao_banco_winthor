# 📊 Tabela: PCREQUISICAOAPI

### Estrutura de Colunas e Restrições

         Tabela      Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREQUISICAOAPI     SISTEMA VARCHAR2(100)               Sistema que recebeu a requisição            OPERACIONAL                        NaN
PCREQUISICAOAPI    HOSTNAME VARCHAR2(100) Nome do servidor em que o sistema está rodando            OPERACIONAL                        NaN
PCREQUISICAOAPI DATAINICIAL          DATE         Data da primeira requisição processada            OPERACIONAL                        NaN
PCREQUISICAOAPI   DATAFINAL          DATE           Data da última requisição processada            OPERACIONAL                        NaN
PCREQUISICAOAPI        HASH VARCHAR2(100)                           Hash de autenticação            OPERACIONAL                        NaN
PCREQUISICAOAPI       DADOS          CLOB                              Dados processados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*