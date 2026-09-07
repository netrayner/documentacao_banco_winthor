# 📊 Tabela: PCGIAF_INDUSTRIA_CFOP

### Estrutura de Colunas e Restrições

               Tabela                Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_INDUSTRIA_CFOP CODAPURGIAF_INDUSTRIA       NUMBER Código da Apuração do GIAF para a Indústria CHAVE ESTRANGEIRA (FK)           PCGIAF_INDUSTRIA
PCGIAF_INDUSTRIA_CFOP      CODGIAF_IND_CFOP       NUMBER     Código do CFOP do GIAF para a Indústria    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_INDUSTRIA_CFOP             CODFISCAL  NUMBER(8,0)              Código Fiscal Operacional CFOP            OPERACIONAL                        NaN
PCGIAF_INDUSTRIA_CFOP           INCENTIVADO  VARCHAR2(2)              Definição do Incentivo do CFOP            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*