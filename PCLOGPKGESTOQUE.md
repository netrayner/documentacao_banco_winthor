# 📊 Tabela: PCLOGPKGESTOQUE

### Estrutura de Colunas e Restrições

         Tabela              Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPKGESTOQUE       NUMTRANSVENDA NUMBER(10,0) Número da transação de entrada            OPERACIONAL                        NaN
PCLOGPKGESTOQUE         NUMTRANSENT NUMBER(10,0)   Número da transação de saída            OPERACIONAL                        NaN
PCLOGPKGESTOQUE           CODFILIAL  VARCHAR2(2)         Código Filial de Venda            OPERACIONAL                        NaN
PCLOGPKGESTOQUE     CODFILIALRETIRA  VARCHAR2(2)           Código Filial Retira            OPERACIONAL                        NaN
PCLOGPKGESTOQUE         CODFILIALNF  VARCHAR2(2)      Código Filial Nota Fiscal            OPERACIONAL                        NaN
PCLOGPKGESTOQUE             CODPROD  NUMBER(6,0)             Código do  produto            OPERACIONAL                        NaN
PCLOGPKGESTOQUE              NUMSEQ NUMBER(20,0)            Número de sequencia            OPERACIONAL                        NaN
PCLOGPKGESTOQUE        NUMTRANSITEM NUMBER(18,0)    Número da transação do item            OPERACIONAL                        NaN
PCLOGPKGESTOQUE                  QT NUMBER(20,6)           Quantidade Gerencial            OPERACIONAL                        NaN
PCLOGPKGESTOQUE              QTCONT NUMBER(20,6)            Quantidade Contábil            OPERACIONAL                        NaN
PCLOGPKGESTOQUE            QTAVARIA NUMBER(20,6)              Quantidade Avária            OPERACIONAL                        NaN
PCLOGPKGESTOQUE         QTBLOQUEADA NUMBER(20,6)           Quantidade Bloqueada            OPERACIONAL                        NaN
PCLOGPKGESTOQUE             CODOPER  VARCHAR2(2)                Código operação            OPERACIONAL                        NaN
PCLOGPKGESTOQUE              STATUS  VARCHAR2(2)                         Status            OPERACIONAL                        NaN
PCLOGPKGESTOQUE MOVESTOQUEGERENCIAL  VARCHAR2(1)    Movimenta Estoque Gerencial            OPERACIONAL                        NaN
PCLOGPKGESTOQUE  MOVESTOQUECONTABIL  VARCHAR2(1)     Movimenta Estoque Contábil            OPERACIONAL                        NaN
PCLOGPKGESTOQUE            MENSAGEM         CLOB               Mensagem de erro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*