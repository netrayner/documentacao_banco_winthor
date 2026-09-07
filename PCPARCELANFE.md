# 📊 Tabela: PCPARCELANFE

### Estrutura de Colunas e Restrições

      Tabela       Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARCELANFE       DUPLIC NUMBER(10,0)                            Número da duplicata            OPERACIONAL                        NaN
PCPARCELANFE        PREST  VARCHAR2(2)                                      Prestação            OPERACIONAL                        NaN
PCPARCELANFE       DTVENC         DATE                             Data de vencimento            OPERACIONAL                        NaN
PCPARCELANFE        VALOR NUMBER(10,2)                             Valor da prestação            OPERACIONAL                        NaN
PCPARCELANFE NUMTRANSACAO NUMBER(10,0)                            Número da transação            OPERACIONAL                        NaN
PCPARCELANFE      TIPOMOV  VARCHAR2(1) Tipo de Movimentação (E = Entrada e S = Saída)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*