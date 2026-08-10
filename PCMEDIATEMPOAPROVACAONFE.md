# 📊 Tabela: PCMEDIATEMPOAPROVACAONFE

### Estrutura de Colunas e Restrições

                  Tabela         Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMEDIATEMPOAPROVACAONFE   NUMTRANSACAO  NUMBER(10,0)                               Numero da transação do documento            OPERACIONAL                        NaN
PCMEDIATEMPOAPROVACAONFE        TIPOMOV   VARCHAR2(1)          Tipo de movimentação do documento(E= Entrada/ S=Saida            OPERACIONAL                        NaN
PCMEDIATEMPOAPROVACAONFE         EVENTO VARCHAR2(100) Identifica qual tipo do evento aconteceu com a nota no momento            OPERACIONAL                        NaN
PCMEDIATEMPOAPROVACAONFE DATAHORAEVENTO          DATE                Data e hora que aconteceu o evento no documento            OPERACIONAL                        NaN
PCMEDIATEMPOAPROVACAONFE        TIPODOC   VARCHAR2(4)                Tipo do documento(Valores: NFE, CTE, MDFE, CCE)            OPERACIONAL                        NaN
PCMEDIATEMPOAPROVACAONFE    SITUACAONFE  NUMBER(10,0)                    Situação do documento, no momento do evento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*