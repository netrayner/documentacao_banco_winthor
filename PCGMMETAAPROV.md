# 📊 Tabela: PCGMMETAAPROV

### Estrutura de Colunas e Restrições

       Tabela     Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMMETAAPROV     CODIGO  NUMBER(10,0)                Código do log    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETAAPROV       DATA          DATE             Data da inclusão            OPERACIONAL                        NaN
PCGMMETAAPROV CODUSUARIO   NUMBER(8,0) Código do usuário do sistema            OPERACIONAL                        NaN
PCGMMETAAPROV   SITUACAO   VARCHAR2(2)             Situação da meta            OPERACIONAL                        NaN
PCGMMETAAPROV OBSERVACAO VARCHAR2(100)       Observação sobre o log            OPERACIONAL                        NaN
PCGMMETAAPROV    CODMETA  NUMBER(10,0)               Código da meta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*