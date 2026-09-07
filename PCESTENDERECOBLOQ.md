# 📊 Tabela: PCESTENDERECOBLOQ

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTENDERECOBLOQ   CODROTINA  NUMBER(5,0)                                 CÓDIGO DA ROTINA DE INSERT            OPERACIONAL                        NaN
PCESTENDERECOBLOQ        DATA         DATE               DATA E HORA DE ENTRADA DE INSERT DO REGISTRO            OPERACIONAL                        NaN
PCESTENDERECOBLOQ     DATAALT         DATE                       DATA E HORA DE ALTERAÇÃO DO REGISTRO            OPERACIONAL                        NaN
PCESTENDERECOBLOQ     CODPROD  NUMBER(6,0)                                          CÓDIGO DO PRODUTO            OPERACIONAL                        NaN
PCESTENDERECOBLOQ CODENDERECO  NUMBER(8,0)                                         CÓDIGO DO ENDEREÇO            OPERACIONAL                        NaN
PCESTENDERECOBLOQ     NUMLOTE VARCHAR2(20)                                             NÚMERO DO LOTE            OPERACIONAL                        NaN
PCESTENDERECOBLOQ       NUMOS NUMBER(10,0)                                 NÚMERO DA ORDEM DE SERVIÇO            OPERACIONAL                        NaN
PCESTENDERECOBLOQ   CODFILIAL  VARCHAR2(2)                                CÓDIGO DA FILIAL DE ESTOQUE            OPERACIONAL                        NaN
PCESTENDERECOBLOQ          QT NUMBER(20,8)                                                 QUANTIDADE            OPERACIONAL                        NaN
PCESTENDERECOBLOQ     CODOPER  VARCHAR2(2) MT PARA MOVIMENTAÇÃO EM TRÂSITO, E B PARA BLOQUEIO SIMPLES            OPERACIONAL                        NaN
PCESTENDERECOBLOQ       DTVAL         DATE                     Data de validade do endereço bloqueado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*