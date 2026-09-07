# 📊 Tabela: PCEVENTOSPEDIDO

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEVENTOSPEDIDO     CODEVENTO  NUMBER(8,0)                           Código do evento    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSPEDIDO      CDMOTIVO  NUMBER(8,0)                           Código do motivo    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSPEDIDO   CODUSURLANC  NUMBER(8,0) Código do funcionário efetuou o lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSPEDIDO        DTLANC         DATE                         Data de lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSPEDIDO NUMTRANSVENDA NUMBER(10,0)               Número de transação de venda            OPERACIONAL                        NaN
PCEVENTOSPEDIDO        NUMPED NUMBER(10,0)                           Número do Pedido    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*