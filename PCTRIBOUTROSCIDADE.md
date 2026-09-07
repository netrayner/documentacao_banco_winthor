# 📊 Tabela: PCTRIBOUTROSCIDADE

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRIBOUTROSCIDADE     CODFILIAL  VARCHAR2(2) Código da filial para vínculo com a PCTRIBOUTROS            OPERACIONAL                        NaN
PCTRIBOUTROSCIDADE            UF  VARCHAR2(2)          Estado, para vínculo com a PCTRIBOUTROS            OPERACIONAL                        NaN
PCTRIBOUTROSCIDADE       PERCISS  NUMBER(4,2)                Percentual de ISS por cidade IBGE            OPERACIONAL                        NaN
PCTRIBOUTROSCIDADE CODCIDADEIBGE NUMBER(10,0)                            Código da cidade IBGE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*