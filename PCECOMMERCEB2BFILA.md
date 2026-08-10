# 📊 Tabela: PCECOMMERCEB2BFILA

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BFILA      CODFILIAL  VARCHAR2(2)          Código da filial da integração B2B            OPERACIONAL                        NaN
PCECOMMERCEB2BFILA TIPOINTEGRACAO  NUMBER(4,0)                   Tipo de integração do B2B            OPERACIONAL                        NaN
PCECOMMERCEB2BFILA         TABELA VARCHAR2(50)               Tabela a ser enviada para B2B            OPERACIONAL                        NaN
PCECOMMERCEB2BFILA             ID VARCHAR2(50) Chave de pesquisa para localizar o registro            OPERACIONAL                        NaN
PCECOMMERCEB2BFILA     DTINCLUSAO         DATE        Data de inclusão do registro na fila            OPERACIONAL                        NaN
PCECOMMERCEB2BFILA     OBSERVACAO VARCHAR2(50)       Observações do registro a ser enviado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*