# 📊 Tabela: PCCONEXOS

### Estrutura de Colunas e Restrições

   Tabela         Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONEXOS           DATA  VARCHAR2(8) Indica a data do registro/processamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONEXOS    CODPROCESSO NUMBER(10,0)             Indica o código do processo.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONEXOS        CODPROD NUMBER(10,0)              Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONEXOS      CODPEDIDO NUMBER(10,0)               Indica o código do pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONEXOS           TIPO  NUMBER(1,0)               Indica o tipo do registro.            OPERACIONAL                        NaN
PCCONEXOS           HORA  VARCHAR2(6) Indica a hora do registro/processamento.            OPERACIONAL                        NaN
PCCONEXOS REFEXTPROCESSO VARCHAR2(20)    Indica o referencia externa processo.            OPERACIONAL                        NaN
PCCONEXOS             QT NUMBER(12,2)                     Indica a quantidade.            OPERACIONAL                        NaN
PCCONEXOS          VUNIT NUMBER(14,4)                 Indica o valor unitário.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*