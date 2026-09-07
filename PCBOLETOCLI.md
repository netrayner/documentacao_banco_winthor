# 📊 Tabela: PCBOLETOCLI

### Estrutura de Colunas e Restrições

     Tabela      Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBOLETOCLI      CODCLI  NUMBER(6,0)                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI NOSSONUMBCO VARCHAR2(30)                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI     POSICAO  VARCHAR2(1)                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI      NUMPED NUMBER(10,0)                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI       BANCO  NUMBER(4,0)                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI        DATA         DATE                                                         NaN            OPERACIONAL                        NaN
PCBOLETOCLI    CODBARRA VARCHAR2(44) Campo para armazenar o valor do código de barras do boleto.            OPERACIONAL                        NaN
PCBOLETOCLI    LINHADIG VARCHAR2(65)  Campo para armazenar o valor da linha digitável do boleto.            OPERACIONAL                        NaN
PCBOLETOCLI   CODFILIAL  VARCHAR2(2)       Gravar o código da filial, amarrado ao boleto gerado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*