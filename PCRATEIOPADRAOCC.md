# 📊 Tabela: PCRATEIOPADRAOCC

### Estrutura de Colunas e Restrições

          Tabela      Coluna   Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRATEIOPADRAOCC CODRATEIOCC   NUMBER(10,0)                     Código do rateio padrão de Centro de Custo            OPERACIONAL                        NaN
PCRATEIOPADRAOCC   DESCRICAO   VARCHAR2(80)                  Descrição do rateio padrão de Centro de Custo            OPERACIONAL                        NaN
PCRATEIOPADRAOCC       ATIVO    VARCHAR2(1) Define se o rateio padrão de Centro de Custo está ativo ou não            OPERACIONAL                        NaN
PCRATEIOPADRAOCC         OBS VARCHAR2(2000)                 Observação do rateio padrão de Centro de Custo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*