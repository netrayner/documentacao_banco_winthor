# 📊 Tabela: PCEXPISCOFINSITEM

### Estrutura de Colunas e Restrições

           Tabela                   Coluna Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXPISCOFINSITEM               CODEXCECAO  NUMBER(6,0)                                                                     Código da exceção PIS/COFINS    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPISCOFINSITEM         TIPOMOVIMENTACAO  VARCHAR2(2)                                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPISCOFINSITEM                CODFISCAL  NUMBER(8,0)                                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPISCOFINSITEM                  SUFRAMA  VARCHAR2(1)                                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPISCOFINSITEM               TIPOPESSOA  VARCHAR2(1)                                                                                              NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCEXPISCOFINSITEM                   PERPIS NUMBER(12,4)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM                PERCOFINS NUMBER(12,4)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM          PISCOFINSRETIDO  VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM      CODSITTRIBPISCOFINS  NUMBER(3,0)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM   CODSITTRIBPISCOFINSDEV  NUMBER(3,0)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM         VLPAUTAPISCOFINS NUMBER(18,6)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM          USAPISCOFINSLIT  VARCHAR2(1)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM         BASEPISCOFINSLIT NUMBER(18,6)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM                 VLPISLIT NUMBER(18,6)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM              VLCOFINSLIT NUMBER(18,6)                                                                                              NaN            OPERACIONAL                        NaN
PCEXPISCOFINSITEM GERABASEPISCOFINSSEMALIQ  VARCHAR2(1) Defina se deve gerar base de PIS/CONFINS mesmo quando não for informado aliquotas de PIS/CONFINS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*