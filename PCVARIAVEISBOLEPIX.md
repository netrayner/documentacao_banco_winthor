# 📊 Tabela: PCVARIAVEISBOLEPIX

### Estrutura de Colunas e Restrições

            Tabela    Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVEISBOLEPIX    CODIGO NUMBER(10,0)                                             Chave primária    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVEISBOLEPIX      NOME VARCHAR2(15)                                           Nome da variável            OPERACIONAL                        NaN
PCVARIAVEISBOLEPIX DESCRICAO VARCHAR2(50)                                      Descrição da variável            OPERACIONAL                        NaN
PCVARIAVEISBOLEPIX  CONSULTA         BLOB                                             Campo Consulta            OPERACIONAL                        NaN
PCVARIAVEISBOLEPIX    STATUS  VARCHAR2(1) Status da variável, sendo V para válido e I para inválido.            OPERACIONAL                        NaN
PCVARIAVEISBOLEPIX SCRIPTSQL         CLOB                             Armazenar o script da consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*