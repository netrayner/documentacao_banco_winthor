# 📊 Tabela: PCCOMPROVANTEENTREGACTE

### Estrutura de Colunas e Restrições

                 Tabela                 Coluna  Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPROVANTEENTREGACTE                 NUMSEQ   NUMBER(3,0)                  Número de sequencia dos eventos    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPROVANTEENTREGACTE           NUMTRANSACAO  NUMBER(16,0)                       Número de transação do CTe    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPROVANTEENTREGACTE               CHAVENFE  VARCHAR2(45)                           Chave de acesso da Nfe            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE          DTHORAENTREGA          DATE          Data e hora que foi realizada a entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE           DOCRECEBEDOR  VARCHAR2(20)             Documento do recebedor da mercadoria            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE          NOMERECEBEDOR  VARCHAR2(60)                  Nome do recebedor da mercadoria            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE               LATITUDE  VARCHAR2(20)         Latitude de onde foi realizada a entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE              LONGITUDE  VARCHAR2(20)        Longitude de onde foi realizada a entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE                 IMAGEM          CLOB                 Imagem do comprovante de entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE            HASHENTREGA          CLOB                   Hash do comprovante de entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE          DTHASHENTREGA          DATE                   Data e hora da geração do hash            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE              CODSTATUS  NUMBER(10,0)              Código do status do envio do evento            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE             DESCSTATUS VARCHAR2(255)           Descrição do status do envio do evento            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE           CODMOTORISTA   NUMBER(8,0)                   Código do motorista da entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE          IDENTIFICADOR  VARCHAR2(60)       Identificador único para o envio do evento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPROVANTEENTREGACTE            PROTOCOLOCE  VARCHAR2(20)    Numero do protocolo do comprovante de entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE             TIPOEVENTO   VARCHAR2(2)       Tipo de evento de entrega do CTe (SU e IN)            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE      NTENTATIVAENTREGA   NUMBER(3,0)                   Número da tentativa de entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE        MOTIVOINSUCESSO   VARCHAR2(1)               Motivo do insucesso: 1, 2, 3 ou 4.            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE JUSTIFICATIVAINSUCESSO VARCHAR2(250)                     Justificativa da não entrega            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE     PROTOCOLOINSUCESSO  VARCHAR2(20)                Protocolo do evento de Insucesso.            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE      DTCANCELINSUCESSO          DATE      Data de cancelamento do evento de Insucesso            OPERACIONAL                        NaN
PCCOMPROVANTEENTREGACTE PROTOCOLOCANCINSUCESSO  VARCHAR2(20) Protocolo de cancelamento do evento de Insucesso            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*