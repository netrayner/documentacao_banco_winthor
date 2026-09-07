# 📊 Tabela: PCDOCELETRONICO

### Estrutura de Colunas e Restrições

         Tabela                   Coluna   Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCELETRONICO             NUMTRANSACAO   NUMBER(10,0)                                             Número Transação.    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCELETRONICO                MOVIMENTO    VARCHAR2(1)                            Tipo de NF(S - Saída,E - Entrada).    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCELETRONICO                   XMLNFE           CLOB                                           Arquivo XML da NFe.            OPERACIONAL                        NaN
PCDOCELETRONICO                   XMLCTE           CLOB                                           Arquivo XML da CTe.            OPERACIONAL                        NaN
PCDOCELETRONICO                   XMLCCE           CLOB                                           Arquivo XML do Cce.            OPERACIONAL                        NaN
PCDOCELETRONICO                  XMLMDFE           CLOB                                          Arquivo XML do MDFe.            OPERACIONAL                        NaN
PCDOCELETRONICO               XMLNFECANC VARCHAR2(4000)                                      NC\tXML DE CANCELAMENTO.            OPERACIONAL                        NaN
PCDOCELETRONICO               XMLNFEINUT VARCHAR2(4000)                                     INC\tXML DE INUTILIZACAO.            OPERACIONAL                        NaN
PCDOCELETRONICO               XMLCTECANC VARCHAR2(4000)                                  XML DE CANCELAMENTO DOS CTEs            OPERACIONAL                        NaN
PCDOCELETRONICO                  XMLNFCE           CLOB                                                XML venda NFCE            OPERACIONAL                        NaN
PCDOCELETRONICO       XMLNFECANCELAMENTO           CLOB                                                           NaN            OPERACIONAL                        NaN
PCDOCELETRONICO       XMLCTECANCELAMENTO           CLOB                                                           NaN            OPERACIONAL                        NaN
PCDOCELETRONICO          XMLCTEDESACORDO           CLOB             XML do do evento de prestação de desacordo do Cte            OPERACIONAL                        NaN
PCDOCELETRONICO      XMLNFCECANCELAMENTO           CLOB                                      XML De cancelamento NFCE            OPERACIONAL                        NaN
PCDOCELETRONICO              XMLASSINADO           CLOB                     Arquivo XML Assinado de NF-e, CT-e, MDF-e            OPERACIONAL                        NaN
PCDOCELETRONICO XMLCTECOMPROVANTEENTREGA           CLOB               XML do evento de comprovante de entrega do CT-e            OPERACIONAL                        NaN
PCDOCELETRONICO               DTMXSALTER           DATE                                                           NaN            OPERACIONAL                        NaN
PCDOCELETRONICO      XMLINSUCESSOENTREGA           CLOB            Contém o XML do Evento de Insucesso de Entrega CTE            OPERACIONAL                        NaN
PCDOCELETRONICO  XMLCANCINSUCESSOENTREGA           CLOB Guardar xml do evento de cancelamento de insucesso na entrega            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*