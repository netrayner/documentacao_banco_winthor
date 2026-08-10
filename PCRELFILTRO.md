# 📊 Tabela: PCRELFILTRO

### Estrutura de Colunas e Restrições

     Tabela         Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELFILTRO   CODRELATORIO   NUMBER(4,0)                            Código do relatorio            OPERACIONAL                        NaN
PCRELFILTRO      CODFILTRO   NUMBER(6,0)                               Código do filtro    CHAVE PRIMÁRIA (PK)                        NaN
PCRELFILTRO      NOMECAMPO VARCHAR2(100)                        Nome do campo da tabela            OPERACIONAL                        NaN
PCRELFILTRO       OPERADOR  VARCHAR2(20)                     Operador da clausula where            OPERACIONAL                        NaN
PCRELFILTRO          VALOR VARCHAR2(100) Valor do filtro referente ao campo selecionado            OPERACIONAL                        NaN
PCRELFILTRO OPERADORLOGICO   VARCHAR2(3)                      Operador logico (and, or)            OPERACIONAL                        NaN
PCRELFILTRO          ORDEM   NUMBER(4,0)                               ORDEM DO FILTRO             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*