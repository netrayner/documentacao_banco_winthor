# 📊 Tabela: PCCNAE

### Estrutura de Colunas e Restrições

Tabela            Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCNAE           CODCNAE  VARCHAR2(60)    Código Nacional Atividade Econômica.     CHAVE PRIMÁRIA (PK)                        NaN
PCCNAE          DESCCNAE VARCHAR2(250) Descrição Nacional Atividade Econômica.             OPERACIONAL                        NaN
PCCNAE          CODATIV1   NUMBER(6,0)                       Código Atividade.  CHAVE ESTRANGEIRA (FK)                    PCATIVI
PCCNAE PERCARGATRIBMEDIA   NUMBER(8,4)     Percentual de carga tributária média            OPERACIONAL                        NaN
PCCNAE         MARGEMMVA   NUMBER(8,4)                          Margem de lucro            OPERACIONAL                        NaN
PCCNAE   PERLIMVENDACNAE  NUMBER(18,6)   Percentual de limite de venda por CNAE            OPERACIONAL                        NaN
PCCNAE        PERCFATMES  NUMBER(18,2)     Percentual sobre o faturamento total            OPERACIONAL                        NaN
PCCNAE    FATMEDIOMENSAL  NUMBER(18,2)        Valor do faturamento médio mensal            OPERACIONAL                        NaN
PCCNAE        DTMXSALTER          DATE                                      NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*