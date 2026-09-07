# 📊 Tabela: PCPARAMETROS2022

### Estrutura de Colunas e Restrições

          Tabela                         Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETROS2022             DTINICIOALTPTABELA         DATE                                               Data Inicio de intervalo de alteração de preço            OPERACIONAL                        NaN
PCPARAMETROS2022                DTFIMALTPTABELA         DATE                                                Data Fim do periodo de atualização do PTABELA            OPERACIONAL                        NaN
PCPARAMETROS2022     SOMENTE_PTABELA_DIF_PVENDA  VARCHAR2(1)           Flag para informar se será feito apenas a atualização dos campos PTABELA <> PVENDA            OPERACIONAL                        NaN
PCPARAMETROS2022 SO_DTALTPTABELA_DIF_DTALTPVEND  VARCHAR2(1) Flag para informar se será feito apenas a atualização dos campos DTALTPTABELA <> DTALTPVENDA            OPERACIONAL                        NaN
PCPARAMETROS2022                      CODFILIAL  VARCHAR2(2)                                                                             Codigo da Filial            OPERACIONAL                        NaN
PCPARAMETROS2022                     ATUALIZADO  VARCHAR2(1)                                                    Flag para indicar se opção foi atualizada            OPERACIONAL                        NaN
PCPARAMETROS2022              CODIGOATUALIZACAO  NUMBER(9,0)                                          Codigo sequencial para controle de chave da tabela.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*