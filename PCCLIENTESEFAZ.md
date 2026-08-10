# 📊 Tabela: PCCLIENTESEFAZ

### Estrutura de Colunas e Restrições

        Tabela       Coluna   Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTESEFAZ         DATA           DATE                       Data da consulta realizada            OPERACIONAL                        NaN
PCCLIENTESEFAZ       CODCLI   NUMBER(10,0)                                Código do cliente            OPERACIONAL                        NaN
PCCLIENTESEFAZ       NUMPED   NUMBER(10,0)                                 Número do pedido            OPERACIONAL                        NaN
PCCLIENTESEFAZ   CODRETORNO   NUMBER(10,0)                       Código de retorno do Sefaz            OPERACIONAL                        NaN
PCCLIENTESEFAZ ATIVONOSEFAZ        CHAR(1)           Estava ativo ou não no ato da consulta            OPERACIONAL                        NaN
PCCLIENTESEFAZ       MOTIVO VARCHAR2(1000)           Motivo do bloqueio do cliente no Sefaz            OPERACIONAL                        NaN
PCCLIENTESEFAZ   CODUSUARIO   NUMBER(10,0) Código do usuário que validou o cliente no Sefaz            OPERACIONAL                        NaN
PCCLIENTESEFAZ     PROGRAMA   VARCHAR2(40)         Nome do programa que realizou a consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*