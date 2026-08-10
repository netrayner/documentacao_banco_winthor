# 📊 Tabela: PCFAIXAIMPOSTOPFC

### Estrutura de Colunas e Restrições

           Tabela          Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFAIXAIMPOSTOPFC          CODIGO  NUMBER(10,0)                            Código            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC      DATAINICIO          DATE           Data de inicio da faixa            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC         DATAFIM          DATE               Data final da faixa            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC         IMPOSTO  VARCHAR2(10)                           Imposto            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC             OBS VARCHAR2(200)                        Observação            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC    VLDEDUCAODEP  NUMBER(18,2)       Valor de dedução dependente            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC      DTEXCLUSAO          DATE                  Data de exclusão            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC CODFUNCEXCLUSAO   NUMBER(8,0) Código do funcionário da exclusão            OPERACIONAL                        NaN
PCFAIXAIMPOSTOPFC        PERCBASE  NUMBER(18,2)                   Percentual base            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*