# 📊 Tabela: PCSERVICOSWMS

### Estrutura de Colunas e Restrições

       Tabela  Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOSWMS  CODIGO  NUMBER(6,0)                                             Codigo do servico            OPERACIONAL                        NaN
PCSERVICOSWMS    NOME VARCHAR2(60)                                               Nome do servico            OPERACIONAL                        NaN
PCSERVICOSWMS   VALOR NUMBER(20,2)                                              Valor do servico            OPERACIONAL                        NaN
PCSERVICOSWMS CODOPER  VARCHAR2(2) Codigo de operacao (E - entrada, M - movimentacao, S - saida)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*