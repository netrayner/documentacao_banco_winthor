# 📊 Tabela: PCLOGPROCESSAMENTONFE

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPROCESSAMENTONFE   NUMTRANSACAO NUMBER(10,0)      Número da transação da MDFe.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROCESSAMENTONFE      MOVIMENTO  VARCHAR2(1) Movimento: [S] Saída [E] Entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROCESSAMENTONFE            LOG         CLOB                   Situação atual.            OPERACIONAL                        NaN
PCLOGPROCESSAMENTONFE DTAHORAGERACAO         DATE           data e hora de geração.            OPERACIONAL                        NaN
PCLOGPROCESSAMENTONFE          ORDEM  NUMBER(6,0)          Ordem a ser apresentado.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*