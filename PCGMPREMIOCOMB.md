# 📊 Tabela: PCGMPREMIOCOMB

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGMPREMIOCOMB       CODIGO NUMBER(10,0)                                            Código da combinação    CHAVE PRIMÁRIA (PK)                        NaN
PCGMPREMIOCOMB    CODPREMIO NUMBER(10,0)                                                Código do prêmio CHAVE ESTRANGEIRA (FK)                 PCGMPREMIO
PCGMPREMIOCOMB CODPARAMCOMB NUMBER(10,0)                Código da combinação da parametrização do prêmio CHAVE ESTRANGEIRA (FK)              PCGMPARAMCOMB
PCGMPREMIOCOMB      GATILHO  VARCHAR2(1) Se combinação é gatilho para outras combinações no mesmo prêmio            OPERACIONAL                        NaN
PCGMPREMIOCOMB         PESO  NUMBER(6,3)                                               Peso do indicador            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*