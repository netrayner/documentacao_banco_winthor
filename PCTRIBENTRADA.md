# 📊 Tabela: PCTRIBENTRADA

### Estrutura de Colunas e Restrições

       Tabela              Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBENTRADA                 NCM  VARCHAR2(20)                         Nomeclatura Comum do Mercosul.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADA           CODFILIAL   VARCHAR2(2)                                      Código da filial.    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCTRIBENTRADA            UFORIGEM   VARCHAR2(2)                                          UF de origem.    CHAVE PRIMÁRIA (PK)                   PCESTADO
PCTRIBENTRADA          TIPOFORNEC   VARCHAR2(1)                                    Tipo do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADA           CODFIGURA   NUMBER(8,0)                              Código figura tributária. CHAVE ESTRANGEIRA (FK)               PCTRIBFIGURA
PCTRIBENTRADA    CODTRIBPISCOFINS   NUMBER(4,0) Código da figura tributária para cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBENTRADA CODEXCECAOPISCOFINS   NUMBER(6,0)                           Código da exceção PIS/COFINS CHAVE ESTRANGEIRA (FK)              PCEXPISCOFINS
PCTRIBENTRADA          CODFUNCCAD   NUMBER(8,0)                      Código do Empregado que Cadastrou            OPERACIONAL                        NaN
PCTRIBENTRADA          DTCADASTRO          DATE                                       Data do Cadastro            OPERACIONAL                        NaN
PCTRIBENTRADA                 OBS VARCHAR2(200)                                  Observação Tributação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*