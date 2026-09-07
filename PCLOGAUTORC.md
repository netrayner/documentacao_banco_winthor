# 📊 Tabela: PCLOGAUTORC

### Estrutura de Colunas e Restrições

     Tabela            Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGAUTORC         NUMPEDIDO NUMBER(10,0)                          Nº Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGAUTORC           TAXAFIN  NUMBER(8,4)                      não utilizado            OPERACIONAL                        NaN
PCLOGAUTORC              DATA         DATE                      Data inclusão            OPERACIONAL                        NaN
PCLOGAUTORC          CODPLPAG  NUMBER(4,0)             Código forma pagamento            OPERACIONAL                        NaN
PCLOGAUTORC           CODFUNC  NUMBER(8,0)              Código do funcionário            OPERACIONAL                        NaN
PCLOGAUTORC         CONDVENDA  NUMBER(5,0)                  Condição da venda            OPERACIONAL                        NaN
PCLOGAUTORC     LIBERALIMCRED  VARCHAR2(1)             Liberar limite credito            OPERACIONAL                        NaN
PCLOGAUTORC           LIMCRED NUMBER(12,2)                  Limite do credito            OPERACIONAL                        NaN
PCLOGAUTORC        VLPENDENTE NUMBER(12,2)                     Valor Pendente            OPERACIONAL                        NaN
PCLOGAUTORC            CODCLI  NUMBER(6,0)                  Código do cliente            OPERACIONAL                        NaN
PCLOGAUTORC           CODUSUR  NUMBER(6,0)                  Código do usuário            OPERACIONAL                        NaN
PCLOGAUTORC      DTUTILIZACAO         DATE                    Data utilização            OPERACIONAL                        NaN
PCLOGAUTORC CODFUNCUTILIZACAO  NUMBER(8,0) Código do funcionário que utilizou            OPERACIONAL                        NaN
PCLOGAUTORC        VLLIBERADO NUMBER(18,6)                     Valor liberado            OPERACIONAL                        NaN
PCLOGAUTORC  NUMPEDUTILIZACAO NUMBER(10,0)         Número do pedido utilizado            OPERACIONAL                        NaN
PCLOGAUTORC  LIBERARPORPEDIDO  VARCHAR2(2)                 Liberar por pedido            OPERACIONAL                        NaN
PCLOGAUTORC     NUMPEDLIBERAR NUMBER(10,0)         Número do pedido a liberar            OPERACIONAL                        NaN
PCLOGAUTORC  CODPLPAGLIBERADO  NUMBER(4,0)    Código forma pagamento liberado            OPERACIONAL                        NaN
PCLOGAUTORC               OBS VARCHAR2(80)                         Observação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*