# 📊 Tabela: PCINTEGRACAOITENS

### Estrutura de Colunas e Restrições

           Tabela       Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOITENS        IDPAI   NUMBER(4,0) numero do registro pcintegracao            OPERACIONAL                        NaN
PCINTEGRACAOITENS       CODIGO  NUMBER(15,0)                   codigo do sql            OPERACIONAL                        NaN
PCINTEGRACAOITENS      NOMEARQ VARCHAR2(200)                 nome do arquivo            OPERACIONAL                        NaN
PCINTEGRACAOITENS DESCRICAOARQ VARCHAR2(200)            Descricao do arquivo            OPERACIONAL                        NaN
PCINTEGRACAOITENS  COMPLEMENTO VARCHAR2(200)            Historico do arquivo            OPERACIONAL                        NaN
PCINTEGRACAOITENS         QSQL          CLOB          Sql salvo pelo cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*