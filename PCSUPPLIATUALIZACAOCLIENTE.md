# 📊 Tabela: PCSUPPLIATUALIZACAOCLIENTE

### Estrutura de Colunas e Restrições

                    Tabela                 Coluna Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLIATUALIZACAOCLIENTE             ATRASODIAS  NUMBER(8,0)                                                                                                 Dias de atraso            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE                CNPJCPF VARCHAR2(14)                                                                                            CNPJ/CPF do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE          CODIGOEMPRESA  VARCHAR2(2)                                                                                   Código da empresa do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE             CODIGOLOJA  VARCHAR2(4)                                                                                      Código da loja do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE                     ID  NUMBER(8,0)                                                                                                Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLIATUALIZACAOCLIENTE   INDICADORCLIENTENOVO  VARCHAR2(5)                                                                                                Cliente é novo?            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE LIMITECOMPRADISPONIVEL NUMBER(12,2)                                                                         Limite de compra disponível do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE      LIMITECOMPRATOTAL NUMBER(12,2)                                                                              Limite de compra total do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE           NUMEROCARTAO VARCHAR2(14)                                                                                    Número do cartão do cliente            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE            RAZAOSOCIAL VARCHAR2(40)                                                                                        Razão social da empresa            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE         SALDODMAISCRED NUMBER(12,2)                                                                                         Saldo do cartão D+Cred            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE                 STATUS VARCHAR2(30)                                                                                        Status do cartão D+Cred            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE                TAXAIOF  NUMBER(6,3)         Taxa de IOF. Utilizado somente quando o Parceiro efetuar a impressão do boleto junto com a Nota Fiscal            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE              TAXAMULTA  NUMBER(6,3)       Taxa de multa. Utilizado somente quando o Parceiro efetuar a impressão do boleto junto com a Nota Fiscal            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE        TAXAPERMANENCIA  NUMBER(6,3) Taxa de permanência. Utilizado somente quando o Parceiro efetuar a impressão do boleto junto com a Nota Fiscal            OPERACIONAL                        NaN
PCSUPPLIATUALIZACAOCLIENTE            DATARETORNO         DATE                                                                      Data de retorno da leitura do arquivo CLI            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*