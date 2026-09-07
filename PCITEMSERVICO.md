# 📊 Tabela: PCITEMSERVICO

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMSERVICO    NUMOSSERVICO  NUMBER(6,0)                                       Identifica o serviço.    CHAVE PRIMÁRIA (PK)            PCORDEMSERVICOI
PCITEMSERVICO         CODPROD  NUMBER(6,0)                                 Indica o código do produto.    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCITEMSERVICO            QTDE NUMBER(22,8)                                        Indica a quantidade.            OPERACIONAL                        NaN
PCITEMSERVICO          PVENDA NUMBER(22,8)                         Indica o preço de venda do produto.            OPERACIONAL                        NaN
PCITEMSERVICO    DEMONSTRACAO  VARCHAR2(1)                 Indica se o produto e do tipo demonstração.            OPERACIONAL                        NaN
PCITEMSERVICO     EQUIPAMENTO  VARCHAR2(1)                       Indica o produto do tipo equipamento.            OPERACIONAL                        NaN
PCITEMSERVICO         PTABELA NUMBER(22,8)                                   Indica o preco de tabela.            OPERACIONAL                        NaN
PCITEMSERVICO        PERCDESC NUMBER(22,8)                            Indica o percentual de desconto.            OPERACIONAL                        NaN
PCITEMSERVICO CODFILIALRETIRA  VARCHAR2(2)                Código da Filial que irá retirar do estoque.            OPERACIONAL                        NaN
PCITEMSERVICO  CODEQUIPAMENTO  NUMBER(6,0)                               Código equipamento do serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMSERVICO         NUMLOTE VARCHAR2(15)                                             Número do lote             OPERACIONAL                        NaN
PCITEMSERVICO   NUMSERIEEQUIP VARCHAR2(30)                              Número de série do equipamento    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMSERVICO     CODDEPOSITO NUMBER(10,0) Código do depósito onde o estoque esta armazenado na filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*