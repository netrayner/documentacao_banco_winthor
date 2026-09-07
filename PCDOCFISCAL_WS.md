# 📊 Tabela: PCDOCFISCAL_WS

### Estrutura de Colunas e Restrições

        Tabela                  Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCFISCAL_WS                  ESTADO   VARCHAR2(5)        Unidade Federada Emissão Documento    CHAVE PRIMÁRIA (PK)        PCDOCFISCAL_ESTADOS
PCDOCFISCAL_WS                AMBIENTE   NUMBER(5,0)         Ambiente de trabalho do DocFiscal    CHAVE PRIMÁRIA (PK)       PCDOCFISCAL_AMBIENTE
PCDOCFISCAL_WS                 SERVICO   NUMBER(5,0)           Serviço ofertado pelo DocFiscal    CHAVE PRIMÁRIA (PK)       PCDOCFISCAL_SERVICOS
PCDOCFISCAL_WS                RECEPCAO VARCHAR2(500)               WS de recepção de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS            RET_RECEPCAO VARCHAR2(500)                 WS de retorno da recepção            OPERACIONAL                        NaN
PCDOCFISCAL_WS             AUTORIZACAO VARCHAR2(500)            WS de autorização de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS         RET_AUTORIZACAO VARCHAR2(500) WS de retorno da autorização do documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS         RECEPCAO_EVENTO VARCHAR2(500)    WS de recepção de eventos de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS            INUTILIZACAO VARCHAR2(500)           WS de Inutilização de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS          CONS_PROTOCOLO VARCHAR2(500)  WS de consulta de protocolo de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS          STATUS_SERVICO VARCHAR2(500)    WS de verificação de status do serviço            OPERACIONAL                        NaN
PCDOCFISCAL_WS                  QRCODE VARCHAR2(500)  Link para geração do QRCODE do documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS            CANCELAMENTO VARCHAR2(500)         WS para cancelamento de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS           CONS_CADASTRO VARCHAR2(500)   WS de consulta cadastro de contribuinte            OPERACIONAL                        NaN
PCDOCFISCAL_WS                DOWNLOAD VARCHAR2(500)             WS para download de documento            OPERACIONAL                        NaN
PCDOCFISCAL_WS       CONS_DESTINATARIO VARCHAR2(500)  WS de consulta contribuinte destinatário            OPERACIONAL                        NaN
PCDOCFISCAL_WS       RECEPCAO_SINCRONO VARCHAR2(500)                   WS de recepção síncrono            OPERACIONAL                        NaN
PCDOCFISCAL_WS CONSULTA_NAO_ENCERRADOS VARCHAR2(500)     WS para consultar mdfe não encerrados            OPERACIONAL                        NaN
PCDOCFISCAL_WS   RECEPCAO_SIMPLIFICADO VARCHAR2(500)      WS de recepção simplificado síncrono            OPERACIONAL                        NaN
PCDOCFISCAL_WS        DISTRIBUICAO_DFE VARCHAR2(500)                 WS de distribuição do DFe            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*