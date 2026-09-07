# 📊 Tabela: PCMSGERROWTA

### Estrutura de Colunas e Restrições

      Tabela       Coluna   Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMSGERROWTA NUMTRANSACAO   NUMBER(10,0)   Numero da transação, vinculado com PCNFSAID e PCNFENT.            OPERACIONAL                        NaN
PCMSGERROWTA       CODMSG   NUMBER(10,0)                                      Código da mensagem.            OPERACIONAL                        NaN
PCMSGERROWTA     MENSAGEM VARCHAR2(1000)                           Descrição da mensagem de erro.            OPERACIONAL                        NaN
PCMSGERROWTA      TIPOMOV    VARCHAR2(1) Tipo da movimentação. 'E' para entrada e 'S' para saída.            OPERACIONAL                        NaN
PCMSGERROWTA     OPERACAO  VARCHAR2(100)         Identificação da operação que gravou a mensagem.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*