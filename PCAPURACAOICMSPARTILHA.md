# 📊 Tabela: PCAPURACAOICMSPARTILHA

### Estrutura de Colunas e Restrições

                Tabela                  Coluna Tipo/Tamanho                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPURACAOICMSPARTILHA               CODFILIAL  VARCHAR2(2)                                        Código da Filial da apuração    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSPARTILHA                 DATAINI         DATE                            Data Inicial do período, conforme rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSPARTILHA                 DATAFIM         DATE                              Data Final do período, conforme rotina    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSPARTILHA              UFORIGDEST  VARCHAR2(2)                                                   UF Origem/Destino    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMSPARTILHA         INDMOVIMENTACAO       NUMBER      Indicador de Movimentação (0 = Sem operação/ 1 = Com operação)            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA       SALDOCREDANTDIFAL NUMBER(22,6)          Saldo credor anterior referente ao diferencial de aliquota            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA       VLTOTDEBITOSDIFAL NUMBER(22,6)                                    Valor total dos debitos do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA           VLOUTDEBDIFAL NUMBER(22,6)                                    Valor de outros debitos do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA             VLTOTDEBFCP NUMBER(22,6)      Valor total do debitos por Saida de Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA          VLTOTCREDDIFAL NUMBER(22,6)                                   Valor total dos Creditos do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA            VLTOTCREDFCP NUMBER(22,6) Valor total dos creditos por entradas de Fundo de Combate a Pobreza            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA          VLOUTCREDDIFAL NUMBER(22,6)                                   Valor de outros creditos do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA        VLSLDDEVANTDIFAL NUMBER(22,6)                                        Saldo devedor antes do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA              VLDEDDIFAL NUMBER(22,6)                          Valor a ser deduzido por apuração do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA              VLRECDIFAL NUMBER(22,6)                              Valor recolhido ou a recolher do Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA    VLSLDCREDTRANSPORTAR NUMBER(22,6)     Valor a transportar para o periodo posterior referente ao Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA             DEBESPDIFAL NUMBER(22,6)                Débitos especiais feitos extra apuração para o Difal            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA         SALDOCREDANTFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA         VLTOTDEBITOSFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA             VLOUTDEBFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA          VLSLDDEVANTFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA                VLDEDFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA                VLRECFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA VLSLDCREDTRANSPORTARFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA               DEBESPFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN
PCAPURACAOICMSPARTILHA            VLOUTCREDFCP NUMBER(22,6)                                                                 NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*