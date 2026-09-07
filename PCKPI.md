# 📊 Tabela: PCKPI

### Estrutura de Colunas e Restrições

Tabela            Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
 PCKPI         CODIGOKPI  NUMBER(20,0)                 Código do KPI    CHAVE PRIMÁRIA (PK)                        NaN
 PCKPI              NOME  VARCHAR2(30)                   Nome do KPI            OPERACIONAL                        NaN
 PCKPI         DESCRICAO VARCHAR2(255)           Detalhamento do KPI            OPERACIONAL                        NaN
 PCKPI               TAG  VARCHAR2(15)       Label Decorativa do KPI            OPERACIONAL                        NaN
 PCKPI              TIPO  VARCHAR2(15)                   Tipo do KPI            OPERACIONAL                        NaN
 PCKPI           TAMANHO  VARCHAR2(15)                Tamanho do KPI            OPERACIONAL                        NaN
 PCKPI        ARQUIVOSQL          CLOB        Select a ser executado            OPERACIONAL                        NaN
 PCKPI       VALORMAXIMO  NUMBER(16,2)        Valor máximo da escala            OPERACIONAL                        NaN
 PCKPI       VALORMINIMO  NUMBER(16,2)        Valor minimo da escala            OPERACIONAL                        NaN
 PCKPI       AREANEGOCIO  VARCHAR2(25)               Area de negocio            OPERACIONAL                        NaN
 PCKPI           PREFIXO   VARCHAR2(2)              Prefixo númerico            OPERACIONAL                        NaN
 PCKPI            SUFIXO   VARCHAR2(2)               Sufixo numerico            OPERACIONAL                        NaN
 PCKPI    INVERTERESCALA       CHAR(1)               Inverter escala            OPERACIONAL                        NaN
 PCKPI            ESTADO  VARCHAR2(60) Estado da ultima consolidação            OPERACIONAL                        NaN
 PCKPI QTDECASASDECIMAIS   NUMBER(1,0)  Quantidade de casas decimais            OPERACIONAL                        NaN
 PCKPI          EDITAVEL       CHAR(1)         Permissão para editar            OPERACIONAL                        NaN
 PCKPI       AGENDAMENTO          CLOB  Agendamento consolidação KPI            OPERACIONAL                        NaN
 PCKPI             ATIVO       CHAR(1)          KPI Ativo ou Inativo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*