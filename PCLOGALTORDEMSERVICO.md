# 📊 Tabela: PCLOGALTORDEMSERVICO

### Estrutura de Colunas e Restrições

              Tabela       Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGALTORDEMSERVICO         DATA           DATE                                     Data            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO      CODFUNC    NUMBER(8,0)                    Código do funcionário            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO    CODROTINA    NUMBER(6,0) Código da rotina que realizou a operação            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO       COLUNA   VARCHAR2(30)                Coluna da tabela alterada            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO     VALORNUM   NUMBER(22,8)                     Valor númerico atual            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO  VALORNUMANT   NUMBER(22,8)                  Valor numérico anterior            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO    VALORALFA VARCHAR2(2000)                 Valor alfanumerico atual            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO VALORALFAANT VARCHAR2(2000)              Valor alfanumerico anterior            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO  OBSERVACOES  VARCHAR2(100)                       Observações do log            OPERACIONAL                        NaN
PCLOGALTORDEMSERVICO      MAQUINA  VARCHAR2(100)          Maquina que realizou a operação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*