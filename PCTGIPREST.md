# 📊 Tabela: PCTGIPREST

### Estrutura de Colunas e Restrições

    Tabela            Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTGIPREST            STATUS VARCHAR2(100)       Status do título com a integração TGI            OPERACIONAL                        NaN
PCTGIPREST           DTENVIO          DATE Data de envio do título para integração TGI            OPERACIONAL                        NaN
PCTGIPREST         DTRETORNO          DATE Data de retorno do título da integração TGI            OPERACIONAL                        NaN
PCTGIPREST       SOLICITACAO  NUMBER(10,0)                       Número da solicitação            OPERACIONAL                        NaN
PCTGIPREST     NUMTRANSVENDA  NUMBER(10,0)               Número da transação de vendas            OPERACIONAL                        NaN
PCTGIPREST             PREST   VARCHAR2(2)                         Prestação do título            OPERACIONAL                        NaN
PCTGIPREST PROTOCOLOPOSTAGEM VARCHAR2(100)                Protocolo de postagem do Tgi            OPERACIONAL                        NaN
PCTGIPREST     DATAPROTOCOLO          DATE                    Data do protocolo do Tgi            OPERACIONAL                        NaN
PCTGIPREST            CUSTAS  NUMBER(18,6)                     Valor da despesa do Tgi            OPERACIONAL                        NaN
PCTGIPREST      PROTOCOLOQWA VARCHAR2(100)                 Protocolo do sistema do Tgi            OPERACIONAL                        NaN
PCTGIPREST      CODTITULOQWA  VARCHAR2(20)           Chave única para o sistema do Tgi            OPERACIONAL                        NaN
PCTGIPREST     CODOCORRENCIA   VARCHAR2(5)     Código da ocorrência informado pelo Tgi            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*