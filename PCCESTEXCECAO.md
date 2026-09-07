# 📊 Tabela: PCCESTEXCECAO

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCESTEXCECAO CODCESTEXCEXAO  NUMBER(6,0)       Código identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCESTEXCECAO     CODSEQCEST  NUMBER(6,0)             Código do cadastro do CEST CHAVE ESTRANGEIRA (FK)                     PCCEST
PCCESTEXCECAO          TIPO1  VARCHAR2(2)             1º tipo de exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO         VALOR1 VARCHAR2(10)            1º valor da exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO          TIPO2  VARCHAR2(2)             2º tipo de exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO         VALOR2 VARCHAR2(10)            2º valor da exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO          TIPO3  VARCHAR2(2)             3º tipo de exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO         VALOR3 VARCHAR2(10)            3º valor da exceção do CEST            OPERACIONAL                        NaN
PCCESTEXCECAO CODSEQCESTNOVO  NUMBER(6,0) Código de  exceção do cadastro do CEST            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*