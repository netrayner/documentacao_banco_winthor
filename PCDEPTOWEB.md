# 📊 Tabela: PCDEPTOWEB

### Estrutura de Colunas e Restrições

    Tabela             Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPTOWEB           CODDEPTO  NUMBER(10,0)    Código do Departamento    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPTOWEB          DESCRICAO VARCHAR2(100) Descrição do Departamento            OPERACIONAL                        NaN
PCDEPTOWEB QTDIASESTSEGURANCA  NUMBER(18,2)   Valor Estoque Segurança            OPERACIONAL                        NaN
PCDEPTOWEB        SITUACAOWEB   VARCHAR2(1)               VARCHAR2(1)            OPERACIONAL                        NaN
PCDEPTOWEB         DTCADASTRO          DATE          Data de cadastro            OPERACIONAL                        NaN
PCDEPTOWEB         DTULTALTER          DATE  Data da ultima alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*