# 📊 Tabela: PCPRESTDNI

### Estrutura de Colunas e Restrições

    Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRESTDNI   NUMTRANSVENDA NUMBER(10,0)      Núm. Transação venda titulo.            OPERACIONAL                        NaN
PCPRESTDNI           PREST  VARCHAR2(2)        Núm.  Prestação do título.            OPERACIONAL                        NaN
PCPRESTDNI           VALOR NUMBER(14,2)                 Valor associação.            OPERACIONAL                        NaN
PCPRESTDNI   NUMTRANSBAIXA NUMBER(10,0)          Núm. Transação da baixa.            OPERACIONAL                        NaN
PCPRESTDNI         DTBAIXA         DATE                    Data da baixa.            OPERACIONAL                        NaN
PCPRESTDNI        CODBANCO  NUMBER(4,0)                  Código do banco.            OPERACIONAL                        NaN
PCPRESTDNI          NUMDOC VARCHAR2(20)               Núm. Identificação.            OPERACIONAL                        NaN
PCPRESTDNI  NUMTRANSORIGEM NUMBER(10,0) Núm. Transação do lançamento DNI.            OPERACIONAL                        NaN
PCPRESTDNI NUMTRANSESTORNO NUMBER(10,0)  Núm. Transação do estorno baixa.            OPERACIONAL                        NaN
PCPRESTDNI  DTESTORNOBAIXA         DATE         Data do estorno da baixa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*