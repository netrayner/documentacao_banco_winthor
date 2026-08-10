# 📊 Tabela: PCGIAF_IMPORTACAO_PROD

### Estrutura de Colunas e Restrições

                Tabela                 Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIAF_IMPORTACAO_PROD CODAPURGIAF_IMPORTACAO       NUMBER Código da Apuração do GIAF para a Importação CHAVE ESTRANGEIRA (FK)          PCGIAF_IMPORTACAO
PCGIAF_IMPORTACAO_PROD       CODGIAF_IMP_PROD       NUMBER  Código do Produto do GIAF para a Importação    CHAVE PRIMÁRIA (PK)                        NaN
PCGIAF_IMPORTACAO_PROD                CODPROD  NUMBER(6,0)                            Código do Produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*