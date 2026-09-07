# 📊 Tabela: PCCOMPLEMENTONFCE

### Estrutura de Colunas e Restrições

           Tabela                 Coluna  Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPLEMENTONFCE               AMBIENTE   VARCHAR2(1)       Ambiente emissão NFCe            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE              CHAVENFCE  VARCHAR2(50)                  Chave NFCe            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE              CODFILIAL   VARCHAR2(2)               Codigo Filial            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE              CODSTATUS   NUMBER(4,0)               Codigo Status            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE                   DATA          DATE                        Data            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE              EXPORTADO   VARCHAR2(1)                   Exportado            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE               MENSAGEM VARCHAR2(250)               Mensagem NFCe            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE               NUMCAIXA   NUMBER(6,0)             Numero do Caixa            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE         NUMCAIXAFISCAL   NUMBER(6,0) Num de Serie e Caixa Fiscal            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE                NUMNOTA  NUMBER(10,0)              Numero da Nota            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE              NUMPEDECF  NUMBER(10,0)               Numerador ECF            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE               OPERACAO   VARCHAR2(2)     Operacao do complemento            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE          PROTOCOLONFCE  VARCHAR2(50)       Protocolo autorizacao            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE DTHORAAUTORIZACAOSEFAZ          DATE  Data e hora de autorizacao            OPERACIONAL                        NaN
PCCOMPLEMENTONFCE                XMLNFCE          CLOB              XML venda NFCE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*