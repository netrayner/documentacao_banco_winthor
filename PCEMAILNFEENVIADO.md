# 📊 Tabela: PCEMAILNFEENVIADO

### Estrutura de Colunas e Restrições

           Tabela       Coluna   Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMAILNFEENVIADO   DTINCLUSAO           DATE                     Data da inclusão do email na fila            OPERACIONAL                        NaN
PCEMAILNFEENVIADO      TIPOMOV    VARCHAR2(1)                                      Entrada ou Saida            OPERACIONAL                        NaN
PCEMAILNFEENVIADO NUMTRANSACAO   NUMBER(10,0)         Número da transação da nota no banco de dados            OPERACIONAL                        NaN
PCEMAILNFEENVIADO      NUMNOTA   NUMBER(10,0)                      Número da nota no banco de dados            OPERACIONAL                        NaN
PCEMAILNFEENVIADO DESTINATARIO   VARCHAR2(60)                         Nome do destinatário do email            OPERACIONAL                        NaN
PCEMAILNFEENVIADO       ORIGEM   VARCHAR2(60) Origem do email (Cliente, Transportadora, Redespacho)            OPERACIONAL                        NaN
PCEMAILNFEENVIADO        EMAIL  VARCHAR2(200)                                  E-mail a ser enviado            OPERACIONAL                        NaN
PCEMAILNFEENVIADO    CODFILIAL    VARCHAR2(2)                                Códifo da filial da NF            OPERACIONAL                        NaN
PCEMAILNFEENVIADO     CHAVENFE   VARCHAR2(44)                             Chave NF-e da nota fiscal            OPERACIONAL                        NaN
PCEMAILNFEENVIADO    TIPOENVIO    VARCHAR2(1)  Tipo do envio (E - Emissão / C - Cancelamento) da NF            OPERACIONAL                        NaN
PCEMAILNFEENVIADO     MENSAGEM VARCHAR2(1000)                       Mensagem sobre o envio do email            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*