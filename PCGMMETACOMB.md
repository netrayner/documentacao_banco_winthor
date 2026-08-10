# 📊 Tabela: PCGMMETACOMB

### Estrutura de Colunas e Restrições

      Tabela                Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMMETACOMB                  DATA           DATE                             Data da meta    CHAVE PRIMÁRIA (PK)                        NaN
PCGMMETACOMB         CODCOMBINACAO   NUMBER(10,0)                     Código da combinação    CHAVE PRIMÁRIA (PK)             PCGMCOMBINACAO
PCGMMETACOMB               CODMETA   NUMBER(10,0)                           Código da meta    CHAVE PRIMÁRIA (PK)                   PCGMMETA
PCGMMETACOMB           CODTIPOMETA   NUMBER(10,0)                   Código do tipo de meta            OPERACIONAL                        NaN
PCGMMETACOMB          CODINDICADOR   NUMBER(10,0)                      Código do indicador            OPERACIONAL                        NaN
PCGMMETACOMB                 VALOR   NUMBER(12,2)                           Valor previsto            OPERACIONAL                        NaN
PCGMMETACOMB          DTFECHAMENTO           DATE               Data do fechamento da meta            OPERACIONAL                        NaN
PCGMMETACOMB           DTPREMIACAO           DATE Data do fechamento da apuração do prêmio            OPERACIONAL                        NaN
PCGMMETACOMB             REALIZADO   NUMBER(15,2)                          Valor realizado            OPERACIONAL                        NaN
PCGMMETACOMB            VLCOMISSAO   NUMBER(16,6)          Valor da comissão por indicador            OPERACIONAL                        NaN
PCGMMETACOMB            VLFATURADO   NUMBER(15,2)             Valor faturado por indicador            OPERACIONAL                        NaN
PCGMMETACOMB           ITEMNOVOADD    VARCHAR2(1)      Se novo item será adicionado a meta            OPERACIONAL                        NaN
PCGMMETACOMB         DTITEMNOVOADD           DATE              Data da adição do item novo            OPERACIONAL                        NaN
PCGMMETACOMB      NOMECOMBENTIDADE VARCHAR2(1000)   Nome da combinação da entidade da meta            OPERACIONAL                        NaN
PCGMMETACOMB          PERCATINGIDO   NUMBER(15,2)                      Percentual atingido            OPERACIONAL                        NaN
PCGMMETACOMB          PERCOMPORIND   NUMBER(15,2)     Percentual de comissão por indicador            OPERACIONAL                        NaN
PCGMMETACOMB              FAIXAINI    NUMBER(8,2)                            Faixa inicial            OPERACIONAL                        NaN
PCGMMETACOMB              FAIXAFIM    NUMBER(8,2)                              Faixa final            OPERACIONAL                        NaN
PCGMMETACOMB              SUBTOTAL   NUMBER(15,2)              Valor subtotal do indicador            OPERACIONAL                        NaN
PCGMMETACOMB PERCPESOINDNIVELATING   NUMBER(15,2)     Percentual do peso do nivel atingido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*