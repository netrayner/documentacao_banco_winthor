# 📊 Tabela: PCPROCESSAMENTODFES

### Estrutura de Colunas e Restrições

             Tabela       Coluna  Tipo/Tamanho                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROCESSAMENTODFES NUMTRANSACAO  NUMBER(10,0)                                                 Numero da transação do documento            OPERACIONAL                        NaN
PCPROCESSAMENTODFES      TIPOMOV   VARCHAR2(1)                            Tipo de movimentação do documento(E= Entrada/ S=Saida            OPERACIONAL                        NaN
PCPROCESSAMENTODFES      TIPODOC   VARCHAR2(4)                                  Tipo do documento(Valores: NFE, CTE, MDFE, CCE)            OPERACIONAL                        NaN
PCPROCESSAMENTODFES       STATUS VARCHAR2(100) Valores: CANCELADO, APROVADO, EM_PROCESSAMENTO, REPROVADO_LOCAL, REPROVADO_SEFAZ            OPERACIONAL                        NaN
PCPROCESSAMENTODFES     DATAHORA          DATE                                  Data e hora que o documento recebeu este status            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*