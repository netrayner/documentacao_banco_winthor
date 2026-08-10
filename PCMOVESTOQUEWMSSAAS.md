# 📊 Tabela: PCMOVESTOQUEWMSSAAS

### Estrutura de Colunas e Restrições

             Tabela        Coluna Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVESTOQUEWMSSAAS IDENTIFICADOR NUMBER(10,0)                   Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVESTOQUEWMSSAAS     CODFILIAL  VARCHAR2(2)                   Código Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVESTOQUEWMSSAAS       CODPROD NUMBER(10,0)               Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVESTOQUEWMSSAAS       CODOPER  VARCHAR2(2) Tipo de Operação: Entrada/Saída            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS            QT NUMBER(20,6)            Quantidade do ajuste            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS        ORIGEM VARCHAR2(50)             Origem Movimentação            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS       NUMLOTE VARCHAR2(20)                  Número do lote            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS  DATAVALIDADE         DATE                Data de validade            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS   DATACRIACAO         DATE                 Data de criação            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS      DTCANCEL         DATE            Data de cancelamento            OPERACIONAL                        NaN
PCMOVESTOQUEWMSSAAS DTFINALIZACAO         DATE                   DTFINALIZACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*