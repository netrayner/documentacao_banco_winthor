# 📊 Tabela: PCLOGVARIAVEISPEDIDO

### Estrutura de Colunas e Restrições

              Tabela        Coluna Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGVARIAVEISPEDIDO         DTLOG         DATE            Data do Log            OPERACIONAL                        NaN
PCLOGVARIAVEISPEDIDO        NUMPED NUMBER(12,0)       Numero do Pedido            OPERACIONAL                        NaN
PCLOGVARIAVEISPEDIDO        NUMCAR NUMBER(10,0) Numero do Carregamento            OPERACIONAL                        NaN
PCLOGVARIAVEISPEDIDO NUMTRANSVENDA NUMBER(12,0)    Numero da Transação            OPERACIONAL                        NaN
PCLOGVARIAVEISPEDIDO    OBSERVACAO         CLOB      Observação do Log            OPERACIONAL                        NaN
PCLOGVARIAVEISPEDIDO        ROTINA VARCHAR2(30)         Nome da Rotina            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*