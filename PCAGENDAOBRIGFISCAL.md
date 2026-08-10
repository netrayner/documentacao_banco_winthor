# 📊 Tabela: PCAGENDAOBRIGFISCAL

### Estrutura de Colunas e Restrições

             Tabela                   Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDAOBRIGFISCAL                CODAGENDA  NUMBER(6,0)                           Codigo da Agenda    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDAOBRIGFISCAL               DESCAGENDA VARCHAR2(40)                        Descricao da Agenda            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL             CODOBRFISCAL  NUMBER(6,0)                 Codigo da Obrigação Fiscal            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL         CONSIDERADIAUTIL  VARCHAR2(1)              Considerar somente dias uteis            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL      CONSIDERASABADOUTIL  VARCHAR2(1)                  Considera sabado dia util            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL           QTDIASLEMBRETE  NUMBER(3,0)          Enviar recados apartir de que dia            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL              QTDIASAVISO  NUMBER(2,0)   Enviar recado de quantos em quantos dias            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL CONTINUALEMBRETEAPOSVENC  VARCHAR2(1)                  Lembrar após o vencimento            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL          DESCARTARAGENDA  VARCHAR2(1)                           Descartar agenda            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL            MATRICULALANC  NUMBER(8,0) Matricula do funcionário que lançou agenda            OPERACIONAL                        NaN
PCAGENDAOBRIGFISCAL                 DATALANC         DATE             Data de lançamento do registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*