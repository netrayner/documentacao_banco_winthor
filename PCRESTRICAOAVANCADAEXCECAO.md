# 📊 Tabela: PCRESTRICAOAVANCADAEXCECAO

### Estrutura de Colunas e Restrições

                    Tabela         Coluna  Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRESTRICAOAVANCADAEXCECAO         CODIGO  NUMBER(10,0)                 Código da restrição avançada            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO      CODCONFIG   NUMBER(4,0) Código da configuração da restrição avançada            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO       NUMREGRA   NUMBER(2,0)                              Número da regra            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO       OPERADOR  VARCHAR2(15)                          Operador da exceção            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO  VALOR_VARCHAR VARCHAR2(100)             Valor em alfanumérico da exceção            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO INICIAL_NUMBER  NUMBER(10,2)         Valor inicial em numérico da exceção            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO   FINAL_NUMBER  NUMBER(10,2)           Valor final em numérico da exceção            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO   INICIAL_DATE          DATE           Valor inicial em data da restrição            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO     FINAL_DATE          DATE               Valor final em data da exceção            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO  DATA_CORRENTE   VARCHAR2(1)                          Usa a data corrente            OPERACIONAL                        NaN
PCRESTRICAOAVANCADAEXCECAO    NUMCRITERIO   NUMBER(2,0)                           Número do Critério            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*