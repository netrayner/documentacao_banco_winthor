# 📊 Tabela: PCLISTAPRESENTEI

### Estrutura de Colunas e Restrições

          Tabela          Coluna   Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLISTAPRESENTEI        NUMLISTA    NUMBER(6,0)                    Número de Identificação da Lista    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAPRESENTEI          NUMSEQ    NUMBER(5,0)                           Número Sequencial do item            OPERACIONAL                        NaN
PCLISTAPRESENTEI     CODAUXILIAR   NUMBER(16,0)                                     Codigo Auxiliar    CHAVE PRIMÁRIA (PK)                        NaN
PCLISTAPRESENTEI         QTITENS   NUMBER(10,2)                                 Quantidade de Itens            OPERACIONAL                        NaN
PCLISTAPRESENTEI             OBS VARCHAR2(4000)                                  Observação do Item            OPERACIONAL                        NaN
PCLISTAPRESENTEI QTITENSVENDIDOS   NUMBER(10,2)                        Quantidade de Itens Vendidos            OPERACIONAL                        NaN
PCLISTAPRESENTEI    QTITENSDEVOL   NUMBER(10,2) QUANTIDADE DE ITENS DEVOLVIDOS DA LISTA DE PRESENTE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*