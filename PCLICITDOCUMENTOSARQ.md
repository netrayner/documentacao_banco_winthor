# 📊 Tabela: PCLICITDOCUMENTOSARQ

### Estrutura de Colunas e Restrições

              Tabela             Coluna   Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLICITDOCUMENTOSARQ         CAMINHOWEB VARCHAR2(1000)           Caminho arquivo web            OPERACIONAL                        NaN
PCLICITDOCUMENTOSARQ CODDOCDIGITALIZADO    NUMBER(6,0) Codigo documento digitalizado            OPERACIONAL                        NaN
PCLICITDOCUMENTOSARQ       CODDOCUMENTO   NUMBER(12,0)           Codigo do documento    CHAVE PRIMÁRIA (PK)                        NaN
PCLICITDOCUMENTOSARQ             NUMSEQ   NUMBER(20,0)           Numero da sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCLICITDOCUMENTOSARQ         CAMINHODIR  VARCHAR2(250)          Caminho do diretorio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*