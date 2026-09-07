# 📊 Tabela: PCMYFROTA_HISTORICO

### Estrutura de Colunas e Restrições

             Tabela              Coluna   Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMYFROTA_HISTORICO          DATAEVENTO           DATE                   Data do registro            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO            MENSAGEM VARCHAR2(4000)              Mesagem da integração            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO              STATUS   VARCHAR2(20)            Status do processamento            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO              EVENTO   VARCHAR2(11)   Qual evento, enviado ou recebido            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO IDINTEGRACAOMYFROTA            RAW Chave de integração do com myfrota            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO            ENTIDADE   VARCHAR2(20)       Serviço que gerou o registro            OPERACIONAL                        NaN
PCMYFROTA_HISTORICO               DADOS           CLOB                                NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*