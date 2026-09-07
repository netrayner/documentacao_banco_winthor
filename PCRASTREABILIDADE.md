# 📊 Tabela: PCRASTREABILIDADE

### Estrutura de Colunas e Restrições

           Tabela          Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRASTREABILIDADE          NUMSEQ NUMBER(10,0)           NÚMERO DE SEQUENCIA    CHAVE PRIMÁRIA (PK)                        NaN
PCRASTREABILIDADE CODFILIALRETIRA  VARCHAR2(2)          CÓDIGO FILIAL RETIRA CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCRASTREABILIDADE         CODPROD  NUMBER(6,0)                CÓDIGO PRODUTO    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCRASTREABILIDADE           QTPED NUMBER(20,6)             QUANTIDADE PEDIDA            OPERACIONAL                        NaN
PCRASTREABILIDADE         QTATEND NUMBER(20,6)           QUANTIDADE ATENDIDA            OPERACIONAL                        NaN
PCRASTREABILIDADE          STATUS  VARCHAR2(1)     STATUS DA RASTREABILIDADE            OPERACIONAL                        NaN
PCRASTREABILIDADE             OBS         CLOB OBSERVAÇÃO DA RASTREABILIDADE            OPERACIONAL                        NaN
PCRASTREABILIDADE          NUMPED NUMBER(10,0)                           NaN    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*