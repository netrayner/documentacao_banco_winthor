# 📊 Tabela: PCFILTROAVANCADOEXCECAO

### Estrutura de Colunas e Restrições

                 Tabela         Coluna  Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFILTROAVANCADOEXCECAO         CODIGO  NUMBER(10,0) Código do filtro avançado            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO      CODCONFIG   NUMBER(4,0)    Código da configuração            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO       NUMREGRA   NUMBER(2,0)           Número da regra            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO       OPERADOR  VARCHAR2(15)       Operador da exceção            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO  VALOR_VARCHAR VARCHAR2(100)             Valor varchar            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO INICIAL_NUMBER  NUMBER(10,2)            Inicial number            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO   FINAL_NUMBER  NUMBER(10,2)              Final number            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO   INICIAL_DATE          DATE              Inicial date            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO     FINAL_DATE          DATE                Final date            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO  DATA_CORRENTE   VARCHAR2(1)             Data corrente            OPERACIONAL                        NaN
PCFILTROAVANCADOEXCECAO    NUMCRITERIO   NUMBER(2,0)        Número do Critério            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*