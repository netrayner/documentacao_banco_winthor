# 📊 Tabela: PCHISTCOBI

### Estrutura de Colunas e Restrições

    Tabela        Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTCOBI     NUMREGCOB NUMBER(10,0)         Número do registro de cobrança.            OPERACIONAL                        NaN
PCHISTCOBI     CODFILIAL  VARCHAR2(2)                       Código da filial.            OPERACIONAL                        NaN
PCHISTCOBI NUMTRANSVENDA NUMBER(10,0)           Número de transação de venda.            OPERACIONAL                        NaN
PCHISTCOBI        DUPLIC NUMBER(10,0)                    Número de duplicata.            OPERACIONAL                        NaN
PCHISTCOBI         PREST  VARCHAR2(2)                                Parcela.            OPERACIONAL                        NaN
PCHISTCOBI        DTVENC         DATE                     Data de vencimento.            OPERACIONAL                        NaN
PCHISTCOBI        ATRASO  NUMBER(6,0)                         Dias de atraso.            OPERACIONAL                        NaN
PCHISTCOBI         VALOR NUMBER(10,2)                        Valor do título.            OPERACIONAL                        NaN
PCHISTCOBI     VALORPREV NUMBER(10,2)               Valor previsto do título.            OPERACIONAL                        NaN
PCHISTCOBI        CODCOB  VARCHAR2(4)                     Código de cobrança.            OPERACIONAL                        NaN
PCHISTCOBI DTPROXCONTATO         DATE                 Data do próximo contato            OPERACIONAL                        NaN
PCHISTCOBI  CODSTATUSCOB  NUMBER(4,0) indica a situação da cobrança do título            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*