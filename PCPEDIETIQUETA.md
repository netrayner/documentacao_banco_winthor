# 📊 Tabela: PCPEDIETIQUETA

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIETIQUETA      NUMPED NUMBER(10,0)                         Indica o número do pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIETIQUETA     CODPROD  NUMBER(6,0)                        Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIETIQUETA      NUMSEQ NUMBER(20,0) Indica o número da sequência do produto no pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIETIQUETA NUMETIQUETA  NUMBER(6,0)            Indica o número da etiqueta do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIETIQUETA    QTPEDIDA NUMBER(20,6)                        Indica a quantidade pedida.            OPERACIONAL                        NaN
PCPEDIETIQUETA  QTSEPARADA NUMBER(20,6)                      Indica a quantidade seperada.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*