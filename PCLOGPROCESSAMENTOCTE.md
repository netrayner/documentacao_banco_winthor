# 📊 Tabela: PCLOGPROCESSAMENTOCTE

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPROCESSAMENTOCTE   NUMTRANSACAO NUMBER(10,0)                    Número da Transação do CT.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROCESSAMENTOCTE            LOG         CLOB                               Situação atual.            OPERACIONAL                        NaN
PCLOGPROCESSAMENTOCTE DTAHORAGERACAO         DATE                       Data e hora de geração.            OPERACIONAL                        NaN
PCLOGPROCESSAMENTOCTE          ORDEM  NUMBER(6,0)                      Ordem a ser apresentado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGPROCESSAMENTOCTE      MOVIMENTO  VARCHAR2(1) Tipo de movimentação (E = Entrada/ S = Saida)    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*