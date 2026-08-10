# 📊 Tabela: PCUEPSSALDOSAID

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUEPSSALDOSAID         CODFILIAL  VARCHAR2(2)                                        Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOSAID       NUMTRANSENT NUMBER(10,0)                          Número de Transação da entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOSAID             DTENT         DATE                                 Data da nota de entrada            OPERACIONAL                        NaN
PCUEPSSALDOSAID     NUMTRANSVENDA NUMBER(10,0)                            Número de Transação da saída    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOSAID           DTSAIDA         DATE                              Data da Transação de Saída            OPERACIONAL                        NaN
PCUEPSSALDOSAID           CODPROD  NUMBER(6,0)                                       Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOSAID            QTCONT NUMBER(20,6)                Quantidade do produto da nota de entrada            OPERACIONAL                        NaN
PCUEPSSALDOSAID    CHAVENFEULTENT VARCHAR2(44)                          Chave da nfe da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOSAID NUMTRANSENTULTENT NUMBER(10,0)                   Número da transação da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOSAID       NUMNFULTENT NUMBER(10,0)                        Número da nota da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOSAID   CODFORNECULTENT  NUMBER(6,0)            Código do fornecedor da última filial origem            OPERACIONAL                        NaN
PCUEPSSALDOSAID       SERIEULTENT  VARCHAR2(3)                   Série da nota da última filial origem            OPERACIONAL                        NaN
PCUEPSSALDOSAID   NUMSEQENTULTENT  NUMBER(5,0)    Número seqencial de entrada do item da filial origem            OPERACIONAL                        NaN
PCUEPSSALDOSAID   CODFILIALULTENT  VARCHAR2(2) Código da filial origem informado na tela para consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*