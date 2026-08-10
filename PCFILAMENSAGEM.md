# 📊 Tabela: PCFILAMENSAGEM

### Estrutura de Colunas e Restrições

        Tabela              Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILAMENSAGEM      QTREPROCESSADO   NUMBER(1,0)                                     Reprocessamento            OPERACIONAL                        NaN
PCFILAMENSAGEM          IDMENSAGEM  NUMBER(10,0) --usar a sequence dfseq_filamensagem pra gerar o id    CHAVE PRIMÁRIA (PK)                        NaN
PCFILAMENSAGEM       DATATRANSACAO          DATE                                   Data da transacao    CHAVE PRIMÁRIA (PK)                        NaN
PCFILAMENSAGEM           CODFILIAL   VARCHAR2(2)                                  --codigo da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCFILAMENSAGEM            NUMCAIXA   NUMBER(4,0)                                     --numero do pdv    CHAVE PRIMÁRIA (PK)                        NaN
PCFILAMENSAGEM             NUMNOTA  NUMBER(10,0)                                   --numero do cupom            OPERACIONAL                        NaN
PCFILAMENSAGEM               SERIE   NUMBER(4,0)                                       --serie sefaz            OPERACIONAL                        NaN
PCFILAMENSAGEM          CHAVESEFAZ  VARCHAR2(44)                                     --chave da nota            OPERACIONAL                        NaN
PCFILAMENSAGEM           PROTOCOLO  VARCHAR2(20)                                         --protocolo            OPERACIONAL                        NaN
PCFILAMENSAGEM        CONTINGENCIA VARCHAR2(100)                        --indica contingencia ou nao            OPERACIONAL                        NaN
PCFILAMENSAGEM           IDEXTERNO VARCHAR2(100)            --id que o pdv ou a integracao vai gerar            OPERACIONAL                        NaN
PCFILAMENSAGEM              STATUS   NUMBER(1,0)                --status de processamento (mandar 0)            OPERACIONAL                        NaN
PCFILAMENSAGEM     QTPROCESSAMENTO   NUMBER(1,0)                     --qtd de vezes de processamento            OPERACIONAL                        NaN
PCFILAMENSAGEM       TIPODOCUMENTO   VARCHAR2(3)                              Indica o tipo de venda            OPERACIONAL                        NaN
PCFILAMENSAGEM        TIPOOPERACAO   VARCHAR2(5)                                   Indica a operação            OPERACIONAL                        NaN
PCFILAMENSAGEM            MENSAGEM          CLOB                     Campo relaciona ao xml da venda            OPERACIONAL                        NaN
PCFILAMENSAGEM        TIPOMENSAGEM   NUMBER(1,0)                                       --json ou xml            OPERACIONAL                        NaN
PCFILAMENSAGEM          CODIGOERRO   NUMBER(4,0)                                --se erro, preencher            OPERACIONAL                        NaN
PCFILAMENSAGEM DATAULTIMAALTERACAO          DATE                          --data da ultima alteracao            OPERACIONAL                        NaN
PCFILAMENSAGEM           PDVORIGEM  VARCHAR2(20)                                   PDV DE LANÇAMENTO            OPERACIONAL                        NaN
PCFILAMENSAGEM           IDWINTHOR VARCHAR2(100)               REPRESENTA O NUMTRANSVENDA OU NUMVALE            OPERACIONAL                        NaN
PCFILAMENSAGEM            SEQDOCTO  NUMBER(10,0)         CAMPO REPRESENTADO PARA INTEGRACAO CONSINCO            OPERACIONAL                        NaN
PCFILAMENSAGEM            TERMINAL VARCHAR2(100)                        Terminal que inseriu a linha            OPERACIONAL                        NaN
PCFILAMENSAGEM       DATADOCUMENTO          DATE                     Data de referencia do documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*