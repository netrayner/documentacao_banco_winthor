# 📊 Tabela: PCVIGENCIAPISCOFINS

### Estrutura de Colunas e Restrições

             Tabela                   Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVIGENCIAPISCOFINS                  CODPROD  NUMBER(6,0)                 Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS                  DATAINI         DATE                      Data inicial    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS                  DATAFIN         DATE                        Data Final    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS         TIPOMOVIMENTACAO  VARCHAR2(2)                   Tipo de entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS                CODFISCAL  NUMBER(8,0)                              CFOP    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS                  SUFRAMA  VARCHAR2(1)                           Suframa    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS               TIPOPESSOA  VARCHAR2(1)                    Tipo de Pessoa    CHAVE PRIMÁRIA (PK)                        NaN
PCVIGENCIAPISCOFINS                   PERPIS NUMBER(12,4)                              %PIS            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS                PERCOFINS NUMBER(12,4)                           %COFINS            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS          PISCOFINSRETIDO  VARCHAR2(1)                 PIS/COFINS Retido            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS      CODSITTRIBPISCOFINS  NUMBER(3,0) Sit.Tributária de PIS/COFINS Ent.            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS   CODSITTRIBPISCOFINSDEV  NUMBER(3,0) Sit.Tributária de PIS/COFINS Dev.            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS         VLPAUTAPISCOFINS NUMBER(18,6)         Valor de Pauta PIS/COFINS            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS          USAPISCOFINSLIT  VARCHAR2(1)           Usa PIS/COFINS Litragem            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS         BASEPISCOFINSLIT NUMBER(18,6)                   Base PIS/COFINS            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS                 VLPISLIT NUMBER(18,6)             Valor de PIS Litragem            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS              VLCOFINSLIT NUMBER(18,6)          Valor de COFINS Litragem            OPERACIONAL                        NaN
PCVIGENCIAPISCOFINS GERABASEPISCOFINSSEMALIQ  VARCHAR2(1) Gera Base PIS/COFINS sem Alíquota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*