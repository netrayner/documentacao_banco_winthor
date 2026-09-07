# 📊 Tabela: PCESTOQUEDEPOSITO

### Estrutura de Colunas e Restrições

           Tabela            Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTOQUEDEPOSITO         CODFILIAL   VARCHAR2(2)                               Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCESTOQUEDEPOSITO       CODDEPOSITO  NUMBER(10,0)                             Código do Depósito    CHAVE PRIMÁRIA (PK)                        NaN
PCESTOQUEDEPOSITO         DESCRICAO VARCHAR2(140)                          Descrição do Depósito            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO       PADRAOVENDA   VARCHAR2(1)         Define se o depósito é padrão de venda            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO PADRAOARMAZENAGEM   VARCHAR2(1)   Define se o depósito é padrão de armazenagem            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO            DTLANC          DATE                   Data de Lançamento/Alteração            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO       CODFUNCLANC   NUMBER(8,0)                Cod. Func. Lançamento/Alteração            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO    PADRAORETIRADA   VARCHAR2(1) Indica que é um depósito padrão para retirada.            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO      PADRAOAVARIA   VARCHAR2(2)                   Padrão de avaria do deposito            OPERACIONAL                        NaN
PCESTOQUEDEPOSITO   PADRAOECOMMERCE   VARCHAR2(1)                      DEPOSITO PADRÃO ECOMMERCE            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*