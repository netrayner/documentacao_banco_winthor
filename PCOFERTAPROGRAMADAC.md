# 📊 Tabela: PCOFERTAPROGRAMADAC

### Estrutura de Colunas e Restrições

             Tabela              Coluna Tipo/Tamanho                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOFERTAPROGRAMADAC           CODFILIAL  VARCHAR2(2)                                                      Código da Filial.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC           CODOFERTA  NUMBER(6,0)                                                      Código da Oferta.    CHAVE PRIMÁRIA (PK)                        NaN
PCOFERTAPROGRAMADAC          DESCOFERTA VARCHAR2(60)                                                   Descrição da Oferta.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC           DTINICIAL         DATE                                                          Data Inicial.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC             DTFINAL         DATE                                                            Data Final.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC            DTCANCEL         DATE                                                     Data Cancelamento.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC        MOTIVOCANCEL VARCHAR2(80)                                                   Motivo Cancelamento.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC       CODFUNCCANCEL  NUMBER(8,0)                                       Código Funcionário Cancelamento.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC              DTORIG         DATE                                                           Data Origem.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC         CODFUNCORIG  NUMBER(8,0)                                             Código Funcionário Origem.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC      DTULTALTOFERTA         DATE                                      Data última alteraçãdo na oferta.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC       CODFUNCULTALT  NUMBER(8,0)                                Código Funcionário da última alteração.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC         HORAINICIAL         DATE                                                     Hora inicio oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC           HORAFINAL         DATE                                                      Hora final oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC      VALIDACONVENIO  VARCHAR2(1)                                    Verificar se é valido para convênio            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC       CODTIPOOFERTA  NUMBER(6,0)                                               Código do tipo da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC     CODOFERTAORIGEM  NUMBER(6,0) Define o código da oferta origem que foi replicada para outras filiais            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC      CODPRECOOFERTA  NUMBER(6,0)                                              Código do preço de oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC    PRIORIDADEOFERTA  NUMBER(2,0)                                                 Pedido a ser cancelado            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC CODFILIALINTEGRACAO  NUMBER(3,0)                                         Código da Filial de Integração            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC           DTALTERC5 TIMESTAMP(6)                                                      Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*