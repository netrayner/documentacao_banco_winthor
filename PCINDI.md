# 📊 Tabela: PCINDI

### Estrutura de Colunas e Restrições

Tabela        Coluna Tipo/Tamanho                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDI    NUMINDENIZ NUMBER(10,0)                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDI       CODPROD  NUMBER(6,0)                                                                           NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDI            QT NUMBER(20,6)                                                                           NaN            OPERACIONAL                        NaN
PCINDI        PVENDA NUMBER(12,3)                                                                           NaN            OPERACIONAL                        NaN
PCINDI       PERDESC  NUMBER(5,2)                                                                           NaN            OPERACIONAL                        NaN
PCINDI       PTABELA NUMBER(12,3)                                                                           NaN            OPERACIONAL                        NaN
PCINDI       QTDEVOL NUMBER(14,6)                                         Quantidade devolvida da indenização.             OPERACIONAL                        NaN
PCINDI     NUMULTPED NUMBER(10,0)                                 Número do Último Pedido de Venda do Produto.             OPERACIONAL                        NaN
PCINDI           OBS VARCHAR2(60)                                  Indica a observação da troca (Indenização).             OPERACIONAL                        NaN
PCINDI  NUMNOTAVENDA NUMBER(10,0)                                                Número da nota fiscal de venda            OPERACIONAL                        NaN
PCINDI NUMTRANSVENDA NUMBER(10,0)                                                   Número transação pedido tv1            OPERACIONAL                        NaN
PCINDI      RECOLHER  VARCHAR2(1) Quando marcado indica que a mercadoria será devolvida a empresa pelo cliente.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*