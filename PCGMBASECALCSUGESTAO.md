# 📊 Tabela: PCGMBASECALCSUGESTAO

### Estrutura de Colunas e Restrições

              Tabela            Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMBASECALCSUGESTAO     CODCOMBINACAO NUMBER(10,0)             Código da combinacao da parametrização atual    CHAVE PRIMÁRIA (PK)             PCGMCOMBINACAO
PCGMBASECALCSUGESTAO           NOMINAL  NUMBER(8,2)                              Taxa nominal de crescimento            OPERACIONAL                        NaN
PCGMBASECALCSUGESTAO            AJUSTE  NUMBER(8,2)                                  Taxa de ajuste de preço            OPERACIONAL                        NaN
PCGMBASECALCSUGESTAO         ACRESCIMO  NUMBER(8,2)                               Soma do nominal com ajuste            OPERACIONAL                        NaN
PCGMBASECALCSUGESTAO           CODMETA NUMBER(10,0)                                           Código da meta    CHAVE PRIMÁRIA (PK)                   PCGMMETA
PCGMBASECALCSUGESTAO TOTALSAZONALMEDIA NUMBER(15,2) Total da sazonalidade média para essa combinação da meta            OPERACIONAL                        NaN
PCGMBASECALCSUGESTAO        VLPROJECAO NUMBER(15,2)                   Valor projetado para o mês de dezembro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*