# 📊 Tabela: PCLOGXMLIMPORTADO

### Estrutura de Colunas e Restrições

           Tabela             Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGXMLIMPORTADO          CODFILIAL   VARCHAR2(2)                      Codigo da Filial            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO CHAVEXMLIMPORTACAO VARCHAR2(100)            Chave de importação do XML            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO               DATA          DATE                      Data de cadastro            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO          ROTINACAD  VARCHAR2(40)             Rotina de Cadastro do XML            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO         CODFUNCCAD   NUMBER(8,0) Código do funcionário cadastrou o XML            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO           DTCANCEL          DATE                  Data de Cancelamento            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO      NUMTRANSVENDA  NUMBER(10,0)                    Transação de venda            OPERACIONAL                        NaN
PCLOGXMLIMPORTADO        NUMTRANSENT  NUMBER(10,0)                  Transação de Entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*