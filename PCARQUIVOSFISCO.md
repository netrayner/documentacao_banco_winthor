# 📊 Tabela: PCARQUIVOSFISCO

### Estrutura de Colunas e Restrições

         Tabela             Coluna   Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCARQUIVOSFISCO               DATA           DATE                    Data da geração do arquivo            OPERACIONAL                        NaN
PCARQUIVOSFISCO           NUMCAIXA    NUMBER(4,0)                               Número do caixa            OPERACIONAL                        NaN
PCARQUIVOSFISCO           PENDENTE        CHAR(1) Indica se esta pendente de transmissão ou não            OPERACIONAL                        NaN
PCARQUIVOSFISCO        TIPOARQUIVO        CHAR(1)                Indica se é redução ou estoque            OPERACIONAL                        NaN
PCARQUIVOSFISCO      NUMSERIEEQUIP   VARCHAR2(30)                        Número de série do ECF            OPERACIONAL                        NaN
PCARQUIVOSFISCO   NUMSERIEPLACAMAE   VARCHAR2(50)           Número de série da placa mãe do PDV            OPERACIONAL                        NaN
PCARQUIVOSFISCO         ARQUIVOXML           CLOB                               Conteúdo do XML            OPERACIONAL                        NaN
PCARQUIVOSFISCO          DTINICIAL           DATE                   Data de início para estoque            OPERACIONAL                        NaN
PCARQUIVOSFISCO            DTFINAL           DATE                       Data final para estoque            OPERACIONAL                        NaN
PCARQUIVOSFISCO             RECIBO  VARCHAR2(200)                      Recibo recebido da SEFAZ            OPERACIONAL                        NaN
PCARQUIVOSFISCO ARQUIVORESPOSTAXML VARCHAR2(4000)                       XML de retorno da SEFAZ            OPERACIONAL                        NaN
PCARQUIVOSFISCO          CODFILIAL    VARCHAR2(2)                              Código da filial            OPERACIONAL                        NaN
PCARQUIVOSFISCO  STATUSTRANSMISSAO    NUMBER(1,0)                 Status de transmição arquivos            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*