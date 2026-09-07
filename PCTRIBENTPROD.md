# 📊 Tabela: PCTRIBENTPROD

### Estrutura de Colunas e Restrições

       Tabela              Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBENTPROD             CODPROD   NUMBER(6,0)                                      Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTPROD           CODFILIAL   VARCHAR2(2)                 Código da filial de entrada do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTPROD            UFORIGEM   VARCHAR2(2)                                UF de origem do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTPROD          TIPOFORNEC   VARCHAR2(1)                                     Tipo do fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTPROD           CODFIGURA   NUMBER(8,0)                            Código da figura tributária            OPERACIONAL                        NaN
PCTRIBENTPROD    CODTRIBPISCOFINS   NUMBER(4,0) Código da figura tributária para cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBENTPROD CODEXCECAOPISCOFINS   NUMBER(6,0)                           Código da exceção PIS/COFINS CHAVE ESTRANGEIRA (FK)              PCEXPISCOFINS
PCTRIBENTPROD          CODFUNCCAD   NUMBER(8,0)                      Código do Empregado que Cadastrou            OPERACIONAL                        NaN
PCTRIBENTPROD          DTCADASTRO          DATE                                       Data do Cadastro            OPERACIONAL                        NaN
PCTRIBENTPROD                 OBS VARCHAR2(200)                                  Observação Tributação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*