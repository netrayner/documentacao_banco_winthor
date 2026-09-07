# 📊 Tabela: PCGMMETACOMBCOMPLE

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMMETACOMBCOMPLE           DATA         DATE                         Data da combinação da meta CHAVE ESTRANGEIRA (FK)               PCGMMETACOMB
PCGMMETACOMBCOMPLE  CODCOMBINACAO NUMBER(10,0)                       Código da combinação da meta CHAVE ESTRANGEIRA (FK)               PCGMMETACOMB
PCGMMETACOMBCOMPLE        CODMETA NUMBER(10,0)                                     Código da meta CHAVE ESTRANGEIRA (FK)               PCGMMETACOMB
PCGMMETACOMBCOMPLE      PERCOMMOV NUMBER(12,6)             Percentual de comissão da movimentação            OPERACIONAL                        NaN
PCGMMETACOMBCOMPLE VLFATPORPERCOM NUMBER(12,2) Valor faturado utilizado no percentual de comissão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*