# 📊 Tabela: PCHISTTECHFIN

### Estrutura de Colunas e Restrições

       Tabela            Coluna  Tipo/Tamanho                                                                                                                                                                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTTECHFIN         CODFILIAL   VARCHAR2(2)                                                                                                                                                                                                                                             Codigo da Filial            OPERACIONAL                        NaN
PCHISTTECHFIN    DATAINTEGRACAO  TIMESTAMP(6)                                                                                                                                                                                                                                           Data da Integracao            OPERACIONAL                        NaN
PCHISTTECHFIN               URI VARCHAR2(100)                                                                                                                                                                                                                                            URI da Integracao            OPERACIONAL                        NaN
PCHISTTECHFIN           ARQUIVO          CLOB                                                                                                                                                                                                                                                 Arquivo JSON            OPERACIONAL                        NaN
PCHISTTECHFIN          OPERACAO   VARCHAR2(2) 2 - Receber Status Pre Autorizacao Pedido, 4 - Receber Status Autorizacao Faturamento NF, 8 - Receber Status Cancelamento Nota Fiscal, 99 - Pos Venda, 10 - Devolucao de Nota Fiscal, 11 - Prorrogacao, 12 - Bonificacao, 14 - Liberar NCC, 20 - Conciliacao            OPERACIONAL                        NaN
PCHISTTECHFIN DESCRICAOOPERACAO VARCHAR2(100)                                                                                                                                                                                                                                        Descrição da operação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*