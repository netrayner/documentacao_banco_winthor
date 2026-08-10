# 📊 Tabela: PCCOLECAOVARIAVEISTRIBI

### Estrutura de Colunas e Restrições

                 Tabela         Coluna Tipo/Tamanho                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOLECAOVARIAVEISTRIBI  CODCOLECAOVAR  NUMBER(4,0) Codigo da coleção de variaveis mesmo do cabeçalho PCCOLECAOVARIAVEISTRIBC              OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI   NOMEVARIAVEL VARCHAR2(80)                                                            NOME DA VARIAVEL            OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI DESCRICAOLIVRE VARCHAR2(80)                                                      Descrição da variavel             OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI          VALOR  NUMBER(8,4)                           Valor da variavel utilizado para o calculo do cmv            OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI      DTCRIACAO         DATE                                                  Data de criação da coleção            OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI       DTULTALT         DATE                                                    Data da ultima alteração            OPERACIONAL                        NaN
PCCOLECAOVARIAVEISTRIBI         ROTINA VARCHAR2(40)                                              Rotina que realizou o cadastro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*