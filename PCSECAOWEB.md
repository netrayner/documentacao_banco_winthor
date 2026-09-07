# 📊 Tabela: PCSECAOWEB

### Estrutura de Colunas e Restrições

    Tabela             Coluna  Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSECAOWEB           CODSECAO  NUMBER(10,0)          Codigo da Seção    CHAVE PRIMÁRIA (PK)                        NaN
PCSECAOWEB          DESCRICAO VARCHAR2(100)       Descrição da Seção            OPERACIONAL                        NaN
PCSECAOWEB           CODDEPTO  NUMBER(10,0)   Codigo do Departamento            OPERACIONAL                        NaN
PCSECAOWEB QTDIASESTSEGURANCA  NUMBER(18,2)  Valor Estoque Segurança            OPERACIONAL                        NaN
PCSECAOWEB        SITUACAOWEB   VARCHAR2(1)              VARCHAR2(1)            OPERACIONAL                        NaN
PCSECAOWEB         DTCADASTRO          DATE         Data de cadastro            OPERACIONAL                        NaN
PCSECAOWEB         DTULTALTER          DATE Data de ultima alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*