# 📊 Tabela: PCERRONFSE

### Estrutura de Colunas e Restrições

    Tabela                Coluna   Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCERRONFSE          NUMTRANSACAO   NUMBER(10,0)                  Transação da Movimentação            OPERACIONAL                        NaN
PCERRONFSE             MOVIMENTO    VARCHAR2(1)                            Movimento E e S            OPERACIONAL                        NaN
PCERRONFSE           CODMENSAGEM    NUMBER(6,0) Código Mensagem com vinculo PCMENSAGEMNFSE            OPERACIONAL                        NaN
PCERRONFSE           CODAUXILIAR   NUMBER(10,0)                            Código Auxiliar            OPERACIONAL                        NaN
PCERRONFSE             DESCRICAO VARCHAR2(1000)                       Descrição da Mesnagm            OPERACIONAL                        NaN
PCERRONFSE CODMENSAGEMPREFEITURA  VARCHAR2(100)           Código da Mensagem na Prefeitura            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*