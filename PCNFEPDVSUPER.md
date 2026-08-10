# 📊 Tabela: PCNFEPDVSUPER

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFEPDVSUPER      SEQDOCTO NUMBER(10,0)                               Número sequencial do documento PDV Super.    CHAVE PRIMÁRIA (PK)                        NaN
PCNFEPDVSUPER    NROEMPRESA  NUMBER(3,0)                                             Número da empresa PDV Super    CHAVE PRIMÁRIA (PK)                        NaN
PCNFEPDVSUPER   NROCHECKOUT  NUMBER(3,0)                                                      Número do checkout    CHAVE PRIMÁRIA (PK)                        NaN
PCNFEPDVSUPER        NUMPED NUMBER(10,0)                                                Chave do pedido Winthor.            OPERACIONAL                        NaN
PCNFEPDVSUPER NUMTRANSVENDA NUMBER(10,0)                                       Número identificador da transação            OPERACIONAL                        NaN
PCNFEPDVSUPER       POSICAO  VARCHAR2(1) Se o pedido foi finalizado com sucesso ou não E - Erro / F - Finalizado            OPERACIONAL                        NaN
PCNFEPDVSUPER       DETALHE         CLOB                                  Arquivo json referente o status da NFE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*