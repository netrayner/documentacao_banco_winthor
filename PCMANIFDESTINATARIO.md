# 📊 Tabela: PCMANIFDESTINATARIO

### Estrutura de Colunas e Restrições

             Tabela                Coluna   Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMANIFDESTINATARIO                CODIGO   NUMBER(10,0)                                            Código    CHAVE PRIMÁRIA (PK)                        NaN
PCMANIFDESTINATARIO         TIPODOCUMENTO    NUMBER(1,0)            0-NF-e 1-Cancelamento 2-Evento de CC-e            OPERACIONAL                        NaN
PCMANIFDESTINATARIO    DATARECEBDOCUMENTO           DATE                     Data recebimento do Documento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO             CODFILIAL    VARCHAR2(2)                                  Código da Filial            OPERACIONAL                        NaN
PCMANIFDESTINATARIO                    UF    VARCHAR2(2)                                                UF            OPERACIONAL                        NaN
PCMANIFDESTINATARIO               CNPJCPF   VARCHAR2(18)                                       CNPJ ou CPF            OPERACIONAL                        NaN
PCMANIFDESTINATARIO                    IE   VARCHAR2(14)                                Inscricao Estadual            OPERACIONAL                        NaN
PCMANIFDESTINATARIO                  NOME   VARCHAR2(60)                                Nome/ Razão social            OPERACIONAL                        NaN
PCMANIFDESTINATARIO              CHAVENFE   VARCHAR2(44)                                         Chave Nfe            OPERACIONAL                        NaN
PCMANIFDESTINATARIO           DATAENTRADA           DATE                     Data de entrada da mercadoria            OPERACIONAL                        NaN
PCMANIFDESTINATARIO           DATAEMISSAO           DATE                         Data de emissão Nfe e CCe            OPERACIONAL                        NaN
PCMANIFDESTINATARIO              TIPONOTA    NUMBER(1,0)                                 0=Entrada 1=Saída            OPERACIONAL                        NaN
PCMANIFDESTINATARIO         FINALIDADENFE    NUMBER(1,0)   1=NF-e Normal 2=NF-e Complementar 3=NF-e Ajuste            OPERACIONAL                        NaN
PCMANIFDESTINATARIO           DIGESTVALUE   VARCHAR2(28)                    DigestValue da NF-e Autorizada            OPERACIONAL                        NaN
PCMANIFDESTINATARIO           SITUACAONFE    NUMBER(1,0)               1=Autorizada 2=Cancelada 3=Denegada            OPERACIONAL                        NaN
PCMANIFDESTINATARIO    SITCONFIRMACAODEST    NUMBER(1,0)                         Confirmação Destinatário:            OPERACIONAL                        NaN
PCMANIFDESTINATARIO  DATAAUTORIZACAOSEFAZ           DATE         Data e Hora de autorização de uso da NF-e            OPERACIONAL                        NaN
PCMANIFDESTINATARIO            VLTOTALNFE   NUMBER(13,2)                               Valor total da NF-e            OPERACIONAL                        NaN
PCMANIFDESTINATARIO            TIPOEVENTO    NUMBER(6,0)                               Código do de evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO             SEQEVENTO    NUMBER(2,0)                              Sequencial do evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO       DESCRICAOEVENTO   VARCHAR2(60)                               Descrição do Evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO              CORRECAO VARCHAR2(1000)                             Descrição da Correção            OPERACIONAL                        NaN
PCMANIFDESTINATARIO        FEZDOWNLOADXML    VARCHAR2(1)                             Ralização do download            OPERACIONAL                        NaN
PCMANIFDESTINATARIO              AMBIENTE    VARCHAR2(1)                                     Ambiente NFe.            OPERACIONAL                        NaN
PCMANIFDESTINATARIO                   NSU   NUMBER(15,0)                        Numero de Sequencia Unica.            OPERACIONAL                        NaN
PCMANIFDESTINATARIO         JUSTIFICATIVA  VARCHAR2(255)          Justificativa da operação não realizada.            OPERACIONAL                        NaN
PCMANIFDESTINATARIO             CODSTATUS   NUMBER(10,0)                                 Codigo do Status.            OPERACIONAL                        NaN
PCMANIFDESTINATARIO            DESCSTATUS  VARCHAR2(255)                               Descrição do Status            OPERACIONAL                        NaN
PCMANIFDESTINATARIO            NUMEROLOTE   NUMBER(10,0)                                    Numero de lote            OPERACIONAL                        NaN
PCMANIFDESTINATARIO SITCONFIRMACAODESTANT    NUMBER(1,0)       Situacao de confirmação destinatario Atual.            OPERACIONAL                        NaN
PCMANIFDESTINATARIO             IDREMESSA   NUMBER(10,0)                        Id de remessa manifestação            OPERACIONAL                        NaN
PCMANIFDESTINATARIO     IDREMESSADOWNLOAD   NUMBER(10,0)                            Id de remessa download            OPERACIONAL                        NaN
PCMANIFDESTINATARIO     CODSTATUSDOWNLOAD   NUMBER(10,0)                         Código do Status Download            OPERACIONAL                        NaN
PCMANIFDESTINATARIO    DESCSTATUSDOWNLOAD  VARCHAR2(255)                      Descrição do Status Download            OPERACIONAL                        NaN
PCMANIFDESTINATARIO               MAQUINA   VARCHAR2(64)                     Maquina que realizou o evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO              PROGRAMA   VARCHAR2(64)          Programa ou rotina que realizou o evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO               USUARIO   VARCHAR2(30)               Usuário do SO que realizou o evento            OPERACIONAL                        NaN
PCMANIFDESTINATARIO        QTDEREPROCDOCE    NUMBER(6,0) Quantidade vezes que o documento foi reprocessado            OPERACIONAL                        NaN
PCMANIFDESTINATARIO       PROTOCOLOEVENTO   VARCHAR2(20)                      Protocolo do evento na Sefaz            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*