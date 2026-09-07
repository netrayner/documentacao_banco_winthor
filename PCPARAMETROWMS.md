# 📊 Tabela: PCPARAMETROWMS

### Estrutura de Colunas e Restrições

        Tabela         Coluna   Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETROWMS           NOME   VARCHAR2(50)                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETROWMS          VALOR  VARCHAR2(100)                                 NaN            OPERACIONAL                        NaN
PCPARAMETROWMS      DESCRICAO VARCHAR2(1000)                                 NaN            OPERACIONAL                        NaN
PCPARAMETROWMS      CODFILIAL    VARCHAR2(2)          Indica o codigo da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETROWMS           TIPO   VARCHAR2(20)           Tipo de dado do parâmetro            OPERACIONAL                        NaN
PCPARAMETROWMS         TITULO   VARCHAR2(80)                 Título do parâmetro            OPERACIONAL                        NaN
PCPARAMETROWMS       PROCESSO   VARCHAR2(20)     Processo logístico do parâmetro            OPERACIONAL                        NaN
PCPARAMETROWMS CODAGRUPAMENTO    NUMBER(2,0)          Agrupamento dos parâmetros CHAVE ESTRANGEIRA (FK)        PCPARAMETROWMSAGRUP
PCPARAMETROWMS         NUMSEQ    NUMBER(4,0) Sequência de ordenação do parâmetro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*