# 📊 Tabela: PCGIAF_DISTRIBUICAO_CFOP

### Estrutura de Colunas e Restrições

                  Tabela                   Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_DISTRIBUICAO_CFOP CODAPURGIAF_DISTRIBUICAO       NUMBER Código da Apuração do GIAF para a Distribuição CHAVE ESTRANGEIRA (FK)        PCGIAF_DISTRIBUICAO
PCGIAF_DISTRIBUICAO_CFOP         CODGIAF_DIS_CFOP       NUMBER     Código do CFOP do GIAF para a Distribuição    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_DISTRIBUICAO_CFOP                CODFISCAL  NUMBER(8,0)                 Código Fiscal Operacional CFOP            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO_CFOP              INCENTIVADO  VARCHAR2(2)                 Definição do Incentivo do CFOP            OPERACIONAL                        NaN
PCGIAF_DISTRIBUICAO_CFOP               CODINFITEM  VARCHAR2(8)                     Código descrição do ajuste            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*