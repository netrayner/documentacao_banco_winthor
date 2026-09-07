# 📊 Tabela: PCPRODSIMIL

### Estrutura de Colunas e Restrições

     Tabela      Coluna   Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODSIMIL     CODPROD    NUMBER(6,0)                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSIMIL    CODSIMIL    NUMBER(6,0)                                                  NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODSIMIL CODFUNCLANC    NUMBER(8,0)                                                  NaN            OPERACIONAL                        NaN
PCPRODSIMIL      DTLANC           DATE                                                  NaN            OPERACIONAL                        NaN
PCPRODSIMIL    TIPOPROD    VARCHAR2(1)                            Indica o tipo do produto.            OPERACIONAL                        NaN
PCPRODSIMIL  PRIORIDADE    NUMBER(4,0)                        Indica a ordem de prioridade.            OPERACIONAL                        NaN
PCPRODSIMIL   TIPOTROCA    VARCHAR2(1)   Indica o tipo de troca na substituição automática.            OPERACIONAL                        NaN
PCPRODSIMIL  OBSERVACAO VARCHAR2(2000) Observação no momento de relacionar produto similar.            OPERACIONAL                        NaN
PCPRODSIMIL  DTMXSALTER           DATE                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*