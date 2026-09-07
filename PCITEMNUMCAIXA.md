# 📊 Tabela: PCITEMNUMCAIXA

### Estrutura de Colunas e Restrições

        Tabela                Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMNUMCAIXA             CODFILIAL  VARCHAR2(2)                      FILIAL DO PEDIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA                NUMPED NUMBER(10,0)                      NUMERO DO PEDIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA               CODPROD  NUMBER(6,0)                     CODIGO DO PRODUTO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA               NUMLOTE VARCHAR2(15)                NUMERO DO LOTE DO ITEM    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA                QTCONF NUMBER(20,6)                  QUANTIDADE CONFERIDA            OPERACIONAL                        NaN
PCITEMNUMCAIXA                NUMSEQ NUMBER(20,0) NUMERO DE SEQUENCIA DO ITEM DO PEDIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA                NUMCAR  NUMBER(8,0)      NUMERO DO CARREGAMENTO DO PEDIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA              NUMCAIXA VARCHAR2(10)             NUMERO DA CAIXA DO VOLUME    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMNUMCAIXA           CODFUNCCONF  NUMBER(8,0)                  CODIGO DO CONFERENTE            OPERACIONAL                        NaN
PCITEMNUMCAIXA            CODFUNCSEP  NUMBER(8,0)                   CODIGO DO SEPARADOR            OPERACIONAL                        NaN
PCITEMNUMCAIXA              DATACONF         DATE                   DATA DA CONFERENCIA            OPERACIONAL                        NaN
PCITEMNUMCAIXA           NUMTRANSENT NUMBER(10,0)         NUMERO DE TRANSACAO DO PEDIDO            OPERACIONAL                        NaN
PCITEMNUMCAIXA       PAGTOANTECIPADO  VARCHAR2(4)    SE O PAGAMENTO É OU NÃO ANTECIPADO            OPERACIONAL                        NaN
PCITEMNUMCAIXA NUMVOLUMESCONFERENCIA  NUMBER(4,0)       NUMERO DO VOLUME DA CONFERENCIA            OPERACIONAL                        NaN
PCITEMNUMCAIXA           CODCERTIFIC  NUMBER(8,0)         NUMERO DO CERTIFICADO DO ITEM            OPERACIONAL                        NaN
PCITEMNUMCAIXA              QTRESERV NUMBER(20,6)          QUANTIDADE RESERVADO DO ITEM            OPERACIONAL                        NaN
PCITEMNUMCAIXA            QTINDUZIDA NUMBER(20,6)   QUANTIDADE INDUZIDA DO LOTE NO ITEM            OPERACIONAL                        NaN
PCITEMNUMCAIXA            DTVALIDADE         DATE      DATA DE VALIDADE DO LOTE DO ITEM            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*