# 📊 Tabela: PCLOGCONFERENCIAFRETE

### Estrutura de Colunas e Restrições

               Tabela        Coluna  Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCONFERENCIAFRETE  DATAREGISTRO          DATE                                           Data em que foi executada a alteração            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE    CODUSUARIO   NUMBER(8,0)                                    Código do usuário responsável pela alteração            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE        MOTIVO VARCHAR2(200)                                                             Motivo da alteração            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE           CTE  NUMBER(10,0)                                Número do CTe vinculado ou com financeiro gerado            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE     VINCULADO   VARCHAR2(1) Quando o valor for "S" indica que foi uma vinculação, "N" que foi uma validação            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE    FINANCEIRO   VARCHAR2(1)             Quando o valor for "S" indica que é um log de geração de financeiro            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE VALORANTERIOR  VARCHAR2(10)                                                        Valor antes da alteração            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE    ROTINALANC   VARCHAR2(6)                                                Rotina responsável pelo registro            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE     APLICACAO  VARCHAR2(40)                                       Aplicação utilizada para fazer o registro            OPERACIONAL                        NaN
PCLOGCONFERENCIAFRETE      TERMINAL  VARCHAR2(40)                                       Terminal utilizado pra o fazer o registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*