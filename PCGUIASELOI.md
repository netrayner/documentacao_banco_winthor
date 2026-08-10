# 📊 Tabela: PCGUIASELOI

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                                                                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGUIASELOI       CODGUIA NUMBER(10,0)                                                                                                                             Armazena o código da guia ao qual o selo faz parte    CHAVE PRIMÁRIA (PK)                        NaN
PCGUIASELOI       NUMSELO VARCHAR2(20)                                                                                                                               Armazena o número do selo que faz parte da guia.    CHAVE PRIMÁRIA (PK)                        NaN
PCGUIASELOI        CODCOR NUMBER(10,0)                                                                                                                                    Armazena o código da cor que o selo possui.    CHAVE PRIMÁRIA (PK)                        NaN
PCGUIASELOI     SERIESELO  VARCHAR2(3)                                                                                                                                                      Armazena a Série do Selo.    CHAVE PRIMÁRIA (PK)                        NaN
PCGUIASELOI      OPERACAO  VARCHAR2(3) Armazena as operações realizadas com os selos (" - Devolução, 2 - Inutilização, 3 - Apreensão, 4 - Transferência, 5 - Imprestável, 6 - Substituído, 7 - Venda e 8 - Cancelado"            OPERACIONAL                        NaN
PCGUIASELOI          OBS1 VARCHAR2(50)                                                                                                                                               Observação digitada pelo usuário            OPERACIONAL                        NaN
PCGUIASELOI          OBS2 VARCHAR2(50)                                                                                                                                               Observação digitada pelo usuário            OPERACIONAL                        NaN
PCGUIASELOI       CODUSUR  NUMBER(6,0)                                                                                                                                  Usuário que fez a inclusão da guia no sistema            OPERACIONAL                        NaN
PCGUIASELOI    DTOPERACAO         DATE                                                                                                                                                    Data que ocorreu a operação            OPERACIONAL                        NaN
PCGUIASELOI        NUMPED NUMBER(10,0)                                                                                                                                  Número do pedido de venda que utilizou o selo            OPERACIONAL                        NaN
PCGUIASELOI NUMTRANSVENDA NUMBER(10,0)                                                                                                                               Número da transação de venda que utilizou o selo            OPERACIONAL                        NaN
PCGUIASELOI   NUMTRANSENT NUMBER(10,0)                                                                                                               Número da transação de entrada que realizou a devolução do selo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*