# 📊 Tabela: PCBENEFICFISCALCREDPRESI

### Estrutura de Colunas e Restrições

                  Tabela             Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENEFICFISCALCREDPRESI CODBENEFICIOFISCAL VARCHAR2(10)                Código Benefício Fiscal            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRESI              CODST  NUMBER(4,0) Código da Figura Tributária rotina 514            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRESI         ALIQICMSNF NUMBER(12,4)                    Alíquota ICMS da NF    CHAVE PRIMÁRIA (PK)                        NaN
PCBENEFICFISCALCREDPRESI  ALIQCREDPRESUMIDO NUMBER(12,4)             Alíquota Crédito Presumido            OPERACIONAL                        NaN
PCBENEFICFISCALCREDPRESI             IDPRES NUMBER(10,0)                   ID Crédito Presumido    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*