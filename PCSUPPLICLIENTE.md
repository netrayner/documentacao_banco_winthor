# 📊 Tabela: PCSUPPLICLIENTE

### Estrutura de Colunas e Restrições

         Tabela                 Coluna  Tipo/Tamanho                                                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLICLIENTE                 CODCLI  NUMBER(22,0)                                                                                               Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLICLIENTE     ENVIARCLIENTSUPPLI   VARCHAR2(1)                                                   Indica se envia o cliente para a suppliercard ou não (S ou N)            OPERACIONAL                        NaN
PCSUPPLICLIENTE                QTDFUNC   VARCHAR2(5)                                                                                      Quantidade de funcionários            OPERACIONAL                        NaN
PCSUPPLICLIENTE             DTFUNDACAO          DATE                                                                                     Data de fundação da empresa            OPERACIONAL                        NaN
PCSUPPLICLIENTE            NOMECONTATO  VARCHAR2(40)                                                                                      Nome do contato na empresa            OPERACIONAL                        NaN
PCSUPPLICLIENTE            FATURMENSAL   NUMBER(9,2)                                                                                              Faturamento mensal            OPERACIONAL                        NaN
PCSUPPLICLIENTE       DTPRIMEIRACOMPRA          DATE                                                                              Data da primeira compra do cliente            OPERACIONAL                        NaN
PCSUPPLICLIENTE            TIPOCLIENTE   VARCHAR2(4)                                                              Tipo do cliente, conforme cadastro na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE          EMAILRESPOSTA  VARCHAR2(50)                                                                                               Email de resposta            OPERACIONAL                        NaN
PCSUPPLICLIENTE                  SOCIO  VARCHAR2(40)                                                                Nome de um dos sócios cadastrados na rotina 3312            OPERACIONAL                        NaN
PCSUPPLICLIENTE          DTENVIOSUPPLI          DATE                                                              Data que o cliente foi enviado para a suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE       DTINCLUSAOSUPPLI          DATE                                                                     Data de inclusão do cliente na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE             DTULTALTER          DATE                                                                        Data de última alteração na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE       DTBLOQUEIOSUPPLI          DATE                                                             Data em que o cliente foi bloqueado na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE     VLRLLIMITESUGERIDO   NUMBER(9,2)                                                                              Valor de sugestão para novo limite            OPERACIONAL                        NaN
PCSUPPLICLIENTE   VLRSALDOABERTOSUPPLI  NUMBER(11,2)                                                                        Valor do saldo em aberto na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE           STATUSSUPPLI  VARCHAR2(25) "Status do cliente na SupplierCard (0=Ativo, 1=Bloqueado por r. Crédito, 2=Bloqueado por Atraso, 3=Cancelado)"             OPERACIONAL                        NaN
PCSUPPLICLIENTE              NUMCARTAO  VARCHAR2(14)                                                                                   Número do cartão Suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE             OBSRETORNO VARCHAR2(100)                                                             Observação do retorno da análise de crédito (UPRET)            OPERACIONAL                        NaN
PCSUPPLICLIENTE      DTAPROVACAOCARTAO          DATE                                                                                     Data de aprovação do cartão            OPERACIONAL                        NaN
PCSUPPLICLIENTE       DTULTALTERCADCLI          DATE                                                  Define a data da ultima alteração no Cadastro do Cliente (302)            OPERACIONAL                        NaN
PCSUPPLICLIENTE LIMITECREDDISPONSUPPLI  NUMBER(12,2)                                                                    Limite de crédito disponivel na suppliercard            OPERACIONAL                        NaN
PCSUPPLICLIENTE           CODMOTIVOREJ   VARCHAR2(3)                                                                                    Código do motivo de rejeição            OPERACIONAL                        NaN
PCSUPPLICLIENTE LIMITECOMPRADISPONIVEL  NUMBER(12,2)                                                                                     Limite de compas disponível            OPERACIONAL                        NaN
PCSUPPLICLIENTE             DIASATRASO   NUMBER(5,0)                                                                                                  Dias de atraso            OPERACIONAL                        NaN
PCSUPPLICLIENTE    CODIGOFILIALWINTHOR   VARCHAR2(2)                                                                                     Código da filial do winthor            OPERACIONAL                        NaN
PCSUPPLICLIENTE            EMERGENCIAL   VARCHAR2(1)                                                                                           Limite é emergencial?            OPERACIONAL                        NaN
PCSUPPLICLIENTE    ENVIARCLIENTESUPPLI   VARCHAR2(1)                                                           Indica se envia o cliente para d+cred ou não (S ou N)            OPERACIONAL                        NaN
PCSUPPLICLIENTE             DTMXSALTER          DATE                                                                                                             NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*