# 📊 Tabela: PCPEDCOMPRAOPERLOGITE

### Estrutura de Colunas e Restrições

               Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDCOMPRAOPERLOGITE          NUMPED NUMBER(15,0)                  Número do Pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCOMPRAOPERLOGITE         CODPROD  NUMBER(6,0)                 Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCOMPRAOPERLOGITE          NUMSEQ NUMBER(20,0)              Código do Fornecedor    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCOMPRAOPERLOGITE           QTPED NUMBER(20,6)                      Qtde. Pedida            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGITE         QTATEND NUMBER(20,6)                    Qtde. Atendida            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGITE INTEGRADORAPROD  NUMBER(6,0)  Código da Integradora do Produto            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGITE           PRECO NUMBER(18,6)                  Preço do Produto            OPERACIONAL                        NaN
PCPEDCOMPRAOPERLOGITE        PERCDESC NUMBER(12,4) Percentual de desconto do produto            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*