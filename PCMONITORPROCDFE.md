# 📊 Tabela: PCMONITORPROCDFE

### Estrutura de Colunas e Restrições

          Tabela          Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORPROCDFE              ID  NUMBER(10,0)                                      SEQUENCIAL DA TABELA    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORPROCDFE    NUMTRANSACAO  NUMBER(10,0)                                    TRANSAÇÃO DO DOCUMENTO            OPERACIONAL                        NaN
PCMONITORPROCDFE         TIPOMOV   VARCHAR2(2)                      E=ENTRADA, S=SAIDA, SP= SAIDA PREFAT            OPERACIONAL                        NaN
PCMONITORPROCDFE         TIPODOC   VARCHAR2(3)          IDENTIFICA O TIPO DO DOCUMENTO (NF, CT, MDF, CC)            OPERACIONAL                        NaN
PCMONITORPROCDFE    ORDEM_EVENTO   NUMBER(2,0) CODIGO NUMERICO PARA ORDENAR O EVENTO E FACILITAR A BUSCA            OPERACIONAL                        NaN
PCMONITORPROCDFE DESCRICAOEVENTO VARCHAR2(100)         DESCRIÇÃO DO EVENTO PARA FACILITAR O ENTENDIMENTO            OPERACIONAL                        NaN
PCMONITORPROCDFE  DATAHORAEVENTO          DATE                     DATA HORA DO EVENTO, PARA MEDIR TEMPO            OPERACIONAL                        NaN
PCMONITORPROCDFE        SITUACAO  NUMBER(10,0)                           SITUAÇÃO DO DOCUMENTO NO EVENTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*