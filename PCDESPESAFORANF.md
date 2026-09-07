# 📊 Tabela: PCDESPESAFORANF

### Estrutura de Colunas e Restrições

         Tabela       Coluna  Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESPESAFORANF   CODDESPESA   NUMBER(8,0)             Código da despesa fora da nota    CHAVE PRIMÁRIA (PK)                        NaN
PCDESPESAFORANF  NUMTRANSENT  NUMBER(10,0)               Transação da nota de entrada            OPERACIONAL                        NaN
PCDESPESAFORANF    HISTORICO VARCHAR2(200)                       Historico da despesa            OPERACIONAL                        NaN
PCDESPESAFORANF   HISTORICO2 VARCHAR2(200)        Complemento do historico da despesa            OPERACIONAL                        NaN
PCDESPESAFORANF  LOCALIZACAO  VARCHAR2(20)                     Localização da despesa            OPERACIONAL                        NaN
PCDESPESAFORANF    CODFORNEC   NUMBER(8,0)            Código do fornecedor da despesa            OPERACIONAL                        NaN
PCDESPESAFORANF      CODCONT  NUMBER(10,0)        Código da conta contábil da despesa            OPERACIONAL                        NaN
PCDESPESAFORANF    VLDESPESA  NUMBER(18,6)         Valor da despesa a ser distribuida            OPERACIONAL                        NaN
PCDESPESAFORANF   VLTOTALNFS  NUMBER(18,6) Valor total das notas que compoe a despesa            OPERACIONAL                        NaN
PCDESPESAFORANF PESOTOTALNFS  NUMBER(18,6)  Peso total das notas que compoe a despesa            OPERACIONAL                        NaN
PCDESPESAFORANF  FORMARATEIO   VARCHAR2(1)  Forma de rateio da despesa, peso ou valor            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*