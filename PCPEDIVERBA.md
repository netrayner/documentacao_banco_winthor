# 📊 Tabela: PCPEDIVERBA

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDIVERBA       NUMPED NUMBER(10,0)                         Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIVERBA      CODPROD  NUMBER(6,0)    Código do produto que recebeu rebaixa    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIVERBA       NUMSEQ NUMBER(20,0)            Número sequencial de inserção    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIVERBA     NUMVERBA  NUMBER(6,0)                 Número da verba aplicada    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDIVERBA VLREBAIXACMV NUMBER(18,6) Valor da rebaixa de CMV aplicada no item            OPERACIONAL                        NaN
PCPEDIVERBA         DATA         DATE             Data da aplicação da rebaixa            OPERACIONAL                        NaN
PCPEDIVERBA     DTCANCEL         DATE      Data de cancelamento do pedido/item            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*