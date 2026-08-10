# 📊 Tabela: PCGIAF_IMPORTACAO_CFOP

### Estrutura de Colunas e Restrições

                Tabela                 Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_IMPORTACAO_CFOP CODAPURGIAF_IMPORTACAO       NUMBER Código da Apuração do GIAF para a Importação CHAVE ESTRANGEIRA (FK)          PCGIAF_IMPORTACAO
PCGIAF_IMPORTACAO_CFOP       CODGIAF_IMP_CFOP       NUMBER     Código do CFOP do GIAF para a Importação    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_IMPORTACAO_CFOP              CODFISCAL  NUMBER(8,0)               Código Fiscal Operacional CFOP            OPERACIONAL                        NaN
PCGIAF_IMPORTACAO_CFOP            INCENTIVADO  VARCHAR2(2)               Definição do Incentivo do CFOP            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*