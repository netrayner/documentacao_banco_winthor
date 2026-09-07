# 📊 Tabela: PCAUTORC

### Estrutura de Colunas e Restrições

  Tabela            Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTORC         NUMPEDIDO NUMBER(10,0)                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCAUTORC           TAXAFIN  NUMBER(8,4)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC              DATA         DATE                                                           NaN            OPERACIONAL                        NaN
PCAUTORC          CODPLPAG  NUMBER(4,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC           CODFUNC  NUMBER(8,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC         CONDVENDA  NUMBER(5,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC     LIBERALIMCRED  VARCHAR2(1)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC           LIMCRED NUMBER(12,2)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC        VLPENDENTE NUMBER(12,2)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC            CODCLI  NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC           CODUSUR  NUMBER(6,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC      DTUTILIZACAO         DATE                                                           NaN            OPERACIONAL                        NaN
PCAUTORC CODFUNCUTILIZACAO  NUMBER(8,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC        VLLIBERADO NUMBER(18,6)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC  NUMPEDUTILIZACAO NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC  LIBERARPORPEDIDO  VARCHAR2(2)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC     NUMPEDLIBERAR NUMBER(10,0)                                                           NaN            OPERACIONAL                        NaN
PCAUTORC  CODPLPAGLIBERADO  NUMBER(4,0)             Indica o código do plano de pagamento autorizado.            OPERACIONAL                        NaN
PCAUTORC               OBS VARCHAR2(80) Indica observação/motivo da autorização de limite de crédito.            OPERACIONAL                        NaN
PCAUTORC         ORIGEMPED  VARCHAR2(1)                                    Indica a origem do pedido.            OPERACIONAL                        NaN
PCAUTORC        DTMXSALTER         DATE                                                           NaN            OPERACIONAL                        NaN
PCAUTORC     MELVLLIBERADO NUMBER(18,6)                                                           NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*