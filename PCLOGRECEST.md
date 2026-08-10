# 📊 Tabela: PCLOGRECEST

### Estrutura de Colunas e Restrições

     Tabela       Coluna   Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGRECEST    NUMRECEST   NUMBER(10,0)                 Nr. do processamento do recálculo            OPERACIONAL                        NaN
PCLOGRECEST      CODPROD    NUMBER(6,0)                     Código do produto recalculado            OPERACIONAL                        NaN
PCLOGRECEST    CODFILIAL    VARCHAR2(2)                                 Filial de estoque            OPERACIONAL                        NaN
PCLOGRECEST         DATA           DATE                   Data da realização do recálculo            OPERACIONAL                        NaN
PCLOGRECEST       QT_ANT   NUMBER(18,6)                           Qtde antes do recálculo            OPERACIONAL                        NaN
PCLOGRECEST  DTINICIOREC           DATE                   Data de referência do recálculo            OPERACIONAL                        NaN
PCLOGRECEST      TIPOMOV  VARCHAR2(100)             Movimentações gerenciais ou contábeis            OPERACIONAL                        NaN
PCLOGRECEST QTINICIALREC   NUMBER(18,6)                  Qtde no dia inicial do recálculo            OPERACIONAL                        NaN
PCLOGRECEST      TOT_MOV   NUMBER(18,6) Total movimentado da data de inicio a data atual.            OPERACIONAL                        NaN
PCLOGRECEST     QT_FINAL   NUMBER(18,6)                               Qtde após recálculo            OPERACIONAL                        NaN
PCLOGRECEST          OBS VARCHAR2(2000)                      Observações do processamento            OPERACIONAL                        NaN
PCLOGRECEST      CODFUNC    NUMBER(8,0)              Funcionário que executou o recálculo            OPERACIONAL                        NaN
PCLOGRECEST    DTFIMPROC           DATE              Data e hora do fim do processamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*