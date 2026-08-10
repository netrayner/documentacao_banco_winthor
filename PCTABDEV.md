# 📊 Tabela: PCTABDEV

### Estrutura de Colunas e Restrições

  Tabela                        Coluna Tipo/Tamanho                                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABDEV                      CODDEVOL  NUMBER(4,0)                                                                                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCTABDEV                        MOTIVO VARCHAR2(30)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV                    PERCESTCOM  NUMBER(6,2)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV               ESTORNACOMISSAO  VARCHAR2(1)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV                          TIPO  VARCHAR2(2)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV                      CODCONTA NUMBER(10,0)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV                  CODMOTNESTLE  NUMBER(6,0)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV            CODMOTFORNECNESTLE  NUMBER(6,0)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCTABDEV                 PERCESTCOMMOT  NUMBER(6,2) Percentual de estorno para comissão de motorista. Será aplicado só na geração do relatório de apuração de comissão para motorista.             OPERACIONAL                        NaN
PCTABDEV           MANTERDEBITODESCFIN  VARCHAR2(1)                                                                                    Manter o débito relativo ao desconto financeiro.            OPERACIONAL                        NaN
PCTABDEV                 MANTERCREDITO  VARCHAR2(1)                                                                                    Manter o débito relativo ao desconto financeiro.            OPERACIONAL                        NaN
PCTABDEV               BLOQUEIACLIENTE  VARCHAR2(1)                                                         Motivo da devolução determina uma possível condição de bloqueio do cliente.            OPERACIONAL                        NaN
PCTABDEV RETORNOVENDANAOENTREGUEAODEST  VARCHAR2(1)                                                              Define é uma operação de Retorno de Venda não entregue ao destinatário            OPERACIONAL                        NaN
PCTABDEV                 CODMOTDEVDORI  NUMBER(5,0)                                                                                 Código do motivo de devolução com a integração DORI            OPERACIONAL                        NaN
PCTABDEV                    DTMXSALTER         DATE                                                                                                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*