# 📊 Tabela: PCESTRUTURAAUX

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTRUTURAAUX CODESTRUTURAAUX NUMBER(10,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCESTRUTURAAUX       DESCRICAO VARCHAR2(40)                                          NaN            OPERACIONAL                        NaN
PCESTRUTURAAUX          VOLUME NUMBER(20,8)                                          NaN            OPERACIONAL                        NaN
PCESTRUTURAAUX        CODBARRA NUMBER(14,0)                                          NaN            OPERACIONAL                        NaN
PCESTRUTURAAUX            PESO NUMBER(10,6)               Peso suportado pela estrutura.            OPERACIONAL                        NaN
PCESTRUTURAAUX           NUMOS NUMBER(10,0)                               Número da O.S.            OPERACIONAL                        NaN
PCESTRUTURAAUX        SITUACAO  NUMBER(2,0)                        Situação da estrutura            OPERACIONAL                        NaN
PCESTRUTURAAUX          NUMPED NUMBER(10,0) Indica o número do pedido da OS do carrinho.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*