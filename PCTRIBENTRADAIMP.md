# 📊 Tabela: PCTRIBENTRADAIMP

### Estrutura de Colunas e Restrições

          Tabela                 Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBENTRADAIMP                    NCM  VARCHAR2(15)                  Código NCM da mercadoria de importação.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADAIMP              CODFILIAL   VARCHAR2(2)  Código da Filial que recebe a mercadoria de importação.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADAIMP                CODPAIS  NUMBER(10,0)    Código do País de Origem da mercadoria de importação.    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADAIMP              CODFIGURA   NUMBER(8,0) Código da Figura Tributária da mercadoria de importação.            OPERACIONAL                        NaN
PCTRIBENTRADAIMP    APLICREDBASEIVAPLIQ   VARCHAR2(1)                   Aplicar redução base IVA preço liquido            OPERACIONAL                        NaN
PCTRIBENTRADAIMP APLICREDBASEIVAPLIQBCR   VARCHAR2(1)               Aplicar redução base IVA preço liquido BCR            OPERACIONAL                        NaN
PCTRIBENTRADAIMP       CODTRIBPISCOFINS   NUMBER(4,0)   Código da figura tributária para cálculo do PIS/COFINS            OPERACIONAL                        NaN
PCTRIBENTRADAIMP    CODEXCECAOPISCOFINS   NUMBER(6,0)                             Código da exceção PIS/COFINS CHAVE ESTRANGEIRA (FK)              PCEXPISCOFINS
PCTRIBENTRADAIMP               CODPORTO  NUMBER(10,0)                                          CÓdigo do porto    CHAVE PRIMÁRIA (PK)                        NaN
PCTRIBENTRADAIMP                    OBS VARCHAR2(200)                                    Observação Tributação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*