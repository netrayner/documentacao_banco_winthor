# 📊 Tabela: PCDIFERENCABOLEPIX

### Estrutura de Colunas e Restrições

            Tabela          Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIFERENCABOLEPIX   NUMTRANSVENDA  NUMBER(10,0) Numero de transação de venda    CHAVE PRIMÁRIA (PK)                        NaN
PCDIFERENCABOLEPIX           PREST   VARCHAR2(2)         Numero da prestração    CHAVE PRIMÁRIA (PK)                        NaN
PCDIFERENCABOLEPIX NOSSONUMBOLEPIX  NUMBER(14,0)         Nosso numero bolepix            OPERACIONAL                        NaN
PCDIFERENCABOLEPIX         DTBAIXA          DATE                Data da baixa            OPERACIONAL                        NaN
PCDIFERENCABOLEPIX     VLDIFERENCA  NUMBER(12,2)           Valor da diferença            OPERACIONAL                        NaN
PCDIFERENCABOLEPIX             OBS VARCHAR2(500)                  Observações            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*