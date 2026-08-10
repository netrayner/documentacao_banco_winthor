# 📊 Tabela: PCGIAF_DISTRIBUICAO_PROD

### Estrutura de Colunas e Restrições

                  Tabela                   Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_DISTRIBUICAO_PROD CODAPURGIAF_DISTRIBUICAO       NUMBER Código da Apuração do GIAF para a Distribuição CHAVE ESTRANGEIRA (FK)        PCGIAF_DISTRIBUICAO
PCGIAF_DISTRIBUICAO_PROD         CODGIAF_DIS_PROD       NUMBER  Código do Produto do GIAF para a Distribuição    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_DISTRIBUICAO_PROD                  CODPROD  NUMBER(6,0)                              Código do Produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*