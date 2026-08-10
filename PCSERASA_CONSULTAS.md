# 📊 Tabela: PCSERASA_CONSULTAS

### Estrutura de Colunas e Restrições

            Tabela  Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERASA_CONSULTAS      ID NUMBER(10,0) Código interno da consulta    CHAVE PRIMÁRIA (PK)                        NaN
PCSERASA_CONSULTAS    TIPO VARCHAR2(20)            Tipo do serviço            OPERACIONAL                        NaN
PCSERASA_CONSULTAS    DATA         DATE    Data/Hora da importação            OPERACIONAL                        NaN
PCSERASA_CONSULTAS  TIPOFJ  VARCHAR2(1)  Pessoa Física ou Jurídica            OPERACIONAL                        NaN
PCSERASA_CONSULTAS DOCPESQ VARCHAR2(15)                CPF ou CNPJ            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*