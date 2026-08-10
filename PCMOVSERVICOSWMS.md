# 📊 Tabela: PCMOVSERVICOSWMS

### Estrutura de Colunas e Restrições

          Tabela     Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVSERVICOSWMS CODSERVICO  NUMBER(6,0)                                             Codigo do servico            OPERACIONAL                        NaN
PCMOVSERVICOSWMS         QT  NUMBER(6,0)                             Quantidade de servicos realizados            OPERACIONAL                        NaN
PCMOVSERVICOSWMS      VALOR NUMBER(20,2)                                              Valor do servico            OPERACIONAL                        NaN
PCMOVSERVICOSWMS    CODOPER  VARCHAR2(2) Codigo de operacao (E - entrada, M - movimentacao, S - saida)            OPERACIONAL                        NaN
PCMOVSERVICOSWMS   NUMBONUS  NUMBER(6,0)                                               Numero do bonus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*