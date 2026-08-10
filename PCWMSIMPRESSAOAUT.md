# 📊 Tabela: PCWMSIMPRESSAOAUT

### Estrutura de Colunas e Restrições

           Tabela          Coluna Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSIMPRESSAOAUT       CODFILIAL  VARCHAR2(2) Filial da configuração            OPERACIONAL                        NaN
PCWMSIMPRESSAOAUT         CODCONF  NUMBER(8,0) Código da configuração    CHAVE PRIMÁRIA (PK)                        NaN
PCWMSIMPRESSAOAUT          TIPOOS  NUMBER(4,0)            Tipo da O.S            OPERACIONAL                        NaN
PCWMSIMPRESSAOAUT         TIPODOC      CHAR(1)      Tipo do Documento            OPERACIONAL                        NaN
PCWMSIMPRESSAOAUT NOME_IMPRESSORA VARCHAR2(60)     Nome da Impressora            OPERACIONAL                        NaN
PCWMSIMPRESSAOAUT      DTCADASTRO         DATE       Data de cadastro            OPERACIONAL                        NaN
PCWMSIMPRESSAOAUT       CODROTINA  NUMBER(6,0)       Código da rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*