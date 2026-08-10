# 📊 Tabela: PCHISTPROCESSAMENTONFE

### Estrutura de Colunas e Restrições

                Tabela         Coluna   Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTPROCESSAMENTONFE   NUMTRANSACAO   NUMBER(10,0)                    Número da transação    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTPROCESSAMENTONFE      MOVIMENTO    VARCHAR2(1) Tipo da movimentação(Entrada ou Saida)    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTPROCESSAMENTONFE          ORDEM   NUMBER(10,0)                           Ordem da log    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTPROCESSAMENTONFE            LOG VARCHAR2(1000)                         Mesagem do log            OPERACIONAL                        NaN
PCHISTPROCESSAMENTONFE DTAHORAGERACAO           DATE                Data de inclusão no log            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*