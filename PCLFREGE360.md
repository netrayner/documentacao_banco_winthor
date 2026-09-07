# 📊 Tabela: PCLFREGE360

### Estrutura de Colunas e Restrições

     Tabela              Coluna Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFREGE360              CODREG  NUMBER(6,0)                                      Código do Registro.|Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFREGE360           CODFILIAL  VARCHAR2(2)                                          Código da Filial do relacionamento.|Campo do tipo caracter, de tamanho 2.            OPERACIONAL                        NaN
PCLFREGE360             DATAINI         DATE                                                      Data Inicial do período, conforme rotina.|Campo do tipo data.            OPERACIONAL                        NaN
PCLFREGE360             DATAFIM         DATE                                                        Data Final do período, conforme rotina.|Campo do tipo data.            OPERACIONAL                        NaN
PCLFREGE360      CREDITOENTRADA NUMBER(15,2)              Valor de crédito por entrada no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360         DEBITOSAIDA NUMBER(15,2)                 Valor de débito por saída no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360       OUTROSDEBITOS NUMBER(15,2)                   Valor de outros débitos no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360          ESTCREDITO NUMBER(15,2)               Valor do estorno de crédito no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360      OUTROSCREDITOS NUMBER(15,2)                  Valor de outros créditos no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360           ESTDEBITO NUMBER(15,2)                Valor do estorno de débito no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360            SALDOANT NUMBER(15,2)                   Valor do saldo anterior no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360            DEDUCOES NUMBER(15,2)                         Valor de deduções no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360       ICMSSTENTRADA NUMBER(15,2)              Valor de ICMS ST de Entradas no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360      ICMSSTSAIDAEST NUMBER(15,2)      Valor de ICMS ST de Saídas Estaduais no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360         DIFALIQICMS NUMBER(15,2)            Valor de diferença de alíquota no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360      ICMSIMPORTACAO NUMBER(15,2)               Valor de ICMS de importação no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360       OUTRASOBRICMS NUMBER(15,2)        Valor de Outras Obrigações de ICMS no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360 ICMSSTSAIDAINTEREST NUMBER(15,2) Valor de ICMS ST de Saídas Interestaduais no período.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE360         VLAJDEBITOS NUMBER(15,2)                                                  Valor total dos ajustes a débito decorrentes do documento fiscal.            OPERACIONAL                        NaN
PCLFREGE360        VLAJCREDITOS NUMBER(15,2)                                                 Valor total dos ajustes a crédito decorrentes do documento fiscal.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*