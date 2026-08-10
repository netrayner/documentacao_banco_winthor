# 📊 Tabela: PCGIAF_INDUSTRIA_PROD

### Estrutura de Colunas e Restrições

               Tabela                Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_INDUSTRIA_PROD CODAPURGIAF_INDUSTRIA       NUMBER Código da Apuração do GIAF para a Indústria CHAVE ESTRANGEIRA (FK)           PCGIAF_INDUSTRIA
PCGIAF_INDUSTRIA_PROD      CODGIAF_IND_PROD       NUMBER  Código do Produto do GIAF para a Indústria    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_INDUSTRIA_PROD               CODPROD  NUMBER(6,0)                           Código do Produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*