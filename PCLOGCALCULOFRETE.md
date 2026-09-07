# 📊 Tabela: PCLOGCALCULOFRETE

### Estrutura de Colunas e Restrições

           Tabela         Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCALCULOFRETE   DATAREGISTRO          DATE        Data em que foi executada a alteração            OPERACIONAL                        NaN
PCLOGCALCULOFRETE     CODUSUARIO   NUMBER(8,0) Código do usuário responsável pela alteração            OPERACIONAL                        NaN
PCLOGCALCULOFRETE         NUMCAR  NUMBER(10,0)                       Número do carregamento            OPERACIONAL                        NaN
PCLOGCALCULOFRETE     CODCALCULO  NUMBER(10,0)                   Código do cálculo de frete            OPERACIONAL                        NaN
PCLOGCALCULOFRETE COLUNAALTERADA  VARCHAR2(30)                      Coluna que foi alterada            OPERACIONAL                        NaN
PCLOGCALCULOFRETE  VALORANTERIOR  VARCHAR2(10)                     Valor antes da alteração            OPERACIONAL                        NaN
PCLOGCALCULOFRETE     VALORATUAL  VARCHAR2(10)                       Valor após a alteração            OPERACIONAL                        NaN
PCLOGCALCULOFRETE         MOTIVO VARCHAR2(200)                          Motivo da alteração            OPERACIONAL                        NaN
PCLOGCALCULOFRETE     ROTINALANC   VARCHAR2(6)             Rotina responsável pelo registro            OPERACIONAL                        NaN
PCLOGCALCULOFRETE      APLICACAO  VARCHAR2(40)    Aplicação utilizada para fazer o registro            OPERACIONAL                        NaN
PCLOGCALCULOFRETE       TERMINAL  VARCHAR2(40)    Terminal utilizado pra o fazer o registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*