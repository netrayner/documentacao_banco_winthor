# 📊 Tabela: PCCTEDESTINADO

### Estrutura de Colunas e Restrições

        Tabela               Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCTEDESTINADO               CODIGO NUMBER(10,0)      Código sequencial da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCCTEDESTINADO   DATARECEBDOCUMENTO         DATE Data de recebimento do documento            OPERACIONAL                        NaN
PCCTEDESTINADO            CODFILIAL  VARCHAR2(2)                 Código da filial            OPERACIONAL                        NaN
PCCTEDESTINADO                  NSU NUMBER(15,0)   Numero sequencial único do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO           NUMEROLOTE NUMBER(10,0)                   Número do lote            OPERACIONAL                        NaN
PCCTEDESTINADO             CHAVECTE VARCHAR2(44)                     Chave do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO          DATAEMISSAO         DATE                  Data de emissão            OPERACIONAL                        NaN
PCCTEDESTINADO DATAAUTORIZACAOSEFAZ         DATE     Data de autorização na Sefaz            OPERACIONAL                        NaN
PCCTEDESTINADO          DATAENTRADA         DATE           Data de entrada do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO           VLTOTALCTE NUMBER(13,2)               Valor total do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO             AMBIENTE  VARCHAR2(1)                  Ambiente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO           UFEMITENTE  VARCHAR2(2)            UF do emitente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO      CNPJCPFEMITENTE VARCHAR2(18)             CNPJ/CPF do emitente            OPERACIONAL                        NaN
PCCTEDESTINADO           IEEMITENTE VARCHAR2(14)            IE do emitente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO         NOMEEMITENTE VARCHAR2(60)          Nome do emitente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO     CNPJCPFREMETENTE VARCHAR2(18)     CNPJ/CPF do Remetente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO          IEREMETENTE VARCHAR2(14)           IE do remetente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO        NOMEREMETENTE VARCHAR2(60)         Nome do remetente do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO     CNPJCPFEXPEDIDOR VARCHAR2(18)     CNPJ/CPF do expedidor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO          IEEXPEDIDOR VARCHAR2(14)           IE do expedidor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO        NOMEEXPEDIDOR VARCHAR2(60)         Nome do expedidor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO     CNPJCPFRECEBEDOR VARCHAR2(18)     CNPJ/CPF do recebedor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO          IERECEBEDOR VARCHAR2(14)           IE do recebedor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO       NOMEERECEBEDOR VARCHAR2(60)         Nome do recebedor do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO  CNPJCPFDESTINATARIO VARCHAR2(18)  CNPJ/CPF do destinatário do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO       IEDESTINATARIO VARCHAR2(14)        IE do destinatário do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO     NOMEDESTINATARIO VARCHAR2(60)      Nome do destinatário do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO  CNPJCPFTOMADOROUTRO VARCHAR2(18) CNPJ/CPF do tomador outro do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO       IETOMADOROUTRO VARCHAR2(14)       IE do tomador outro do CTe            OPERACIONAL                        NaN
PCCTEDESTINADO     NOMETOMADOROUTRO VARCHAR2(60)     Nome do tomador outro do CTe            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*