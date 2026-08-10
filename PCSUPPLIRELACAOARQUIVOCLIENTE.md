# 📊 Tabela: PCSUPPLIRELACAOARQUIVOCLIENTE

### Estrutura de Colunas e Restrições

                       Tabela               Coluna Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPPLIRELACAOARQUIVOCLIENTE               CODCLI NUMBER(22,0)                                      Código do cliente            OPERACIONAL                        NaN
PCSUPPLIRELACAOARQUIVOCLIENTE                   ID NUMBER(22,0)                                        Chave da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPPLIRELACAOARQUIVOCLIENTE            IDARQUIVO NUMBER(22,0)            Chave estrangeira da tabela PCSUPPLIARQUIVO            OPERACIONAL                        NaN
PCSUPPLIRELACAOARQUIVOCLIENTE                IDCLI NUMBER(22,0) Chave estrangeira da tabela PCSUPPLIATUALIZACAOCLIENTE            OPERACIONAL                        NaN
PCSUPPLIRELACAOARQUIVOCLIENTE              IDUPRET NUMBER(22,0)     Chave estrangeira da tabela PCSUPPLIRETSOLICITACAO            OPERACIONAL                        NaN
PCSUPPLIRELACAOARQUIVOCLIENTE SOLICITACAOENCERRADA  VARCHAR2(1)                                 Solicitação encerrada?            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*