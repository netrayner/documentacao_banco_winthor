# 📊 Tabela: PCBOLETOTECHFIN

### Estrutura de Colunas e Restrições

         Tabela          Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBOLETOTECHFIN      INTEGRACAO VARCHAR2(100)       Nome da API de integracao            OPERACIONAL                        NaN
PCBOLETOTECHFIN          FILIAL   VARCHAR2(2)                Codigo da filial            OPERACIONAL                        NaN
PCBOLETOTECHFIN   IDENTIFICADOR  VARCHAR2(14)                   Identificador            OPERACIONAL                        NaN
PCBOLETOTECHFIN            TIPO VARCHAR2(100) Tipo do documento da integracao            OPERACIONAL                        NaN
PCBOLETOTECHFIN  DATAINTEGRACAO          DATE              Data da integracao            OPERACIONAL                        NaN
PCBOLETOTECHFIN         ARQUIVO          CLOB               Arquivo em base64            OPERACIONAL                        NaN
PCBOLETOTECHFIN GEROUSEGUNDAVIA   VARCHAR2(1)     GEROU SEGUNDA VIA DO BOLETO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*