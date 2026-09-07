# 📊 Tabela: PCAUXDIASFINANCEIRO

### Estrutura de Colunas e Restrições

             Tabela        Coluna Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUXDIASFINANCEIRO     CODFILIAL  VARCHAR2(2)                                                                     Código da filial            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO   NUMDIAFLUXO  NUMBER(3,0)                                                    Dias usados para cálculo de fluxo            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO  CONSIDERAFDS  NUMBER(1,0)                          Parâmetro para definir se considera ou não finais de semana            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO TIPODIASFLUXO  NUMBER(1,0) Parâmetro para definir se o cálculo dos dias fluxos será apenas com dias financeiros            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO          DATA         DATE                                                          Data do vencimento original            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO    DTVENCCALC         DATE                      Data do vencimento calculada pela FUNC_RETORNADIAUTILFINANCEIRO            OPERACIONAL                        NaN
PCAUXDIASFINANCEIRO        TABELA VARCHAR2(50)                                  Nome da tabela que se refere o calculo do dia util.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*