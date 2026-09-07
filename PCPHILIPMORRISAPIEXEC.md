# 📊 Tabela: PCPHILIPMORRISAPIEXEC

### Estrutura de Colunas e Restrições

               Tabela             Coluna  Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPHILIPMORRISAPIEXEC       NUMEROINDICE   NUMBER(9,0)        Número do índice    CHAVE PRIMÁRIA (PK)                        NaN
PCPHILIPMORRISAPIEXEC        DATAGERACAO          DATE            Data geração            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC      DATAMOVIMENTO          DATE          Data movimento            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC CODIGODISTRIBUIDOR  VARCHAR2(10)     Código distribuidor            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC       LISTAFILIAIS VARCHAR2(255)        Lista de filiais            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC        CAMINHOJSON VARCHAR2(255) Caminho do arquivo JSON            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC             STATUS   NUMBER(1,0)         Status do envio            OPERACIONAL                        NaN
PCPHILIPMORRISAPIEXEC            RETORNO          CLOB        Dados do retorno            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*