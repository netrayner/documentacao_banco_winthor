# 📊 Tabela: PCUEPSSALDOENT

### Estrutura de Colunas e Restrições

        Tabela            Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUEPSSALDOENT         CODFILIAL  VARCHAR2(2)                                        Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOENT       NUMTRANSENT NUMBER(10,0)                          Número de Transação da entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOENT           CODPROD  NUMBER(6,0)                                       Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSALDOENT              DATA         DATE                                 Data da nota de entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT            QTCONT NUMBER(20,6)                Quantidade do produto da nota de entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT             SALDO NUMBER(20,6)                  Saldo Disponível do produto na entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT    CHAVENFEULTENT VARCHAR2(44)                          Chave da nfe da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT NUMTRANSENTULTENT NUMBER(10,0)                   Número da transação da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT       NUMNFULTENT NUMBER(10,0)                        Número da nota da última entrada            OPERACIONAL                        NaN
PCUEPSSALDOENT   CODFORNECULTENT  NUMBER(6,0)            Código do fornecedor da última filial origem            OPERACIONAL                        NaN
PCUEPSSALDOENT       SERIEULTENT  VARCHAR2(3)                   Série da nota da última filial origem            OPERACIONAL                        NaN
PCUEPSSALDOENT   NUMSEQENTULTENT  NUMBER(5,0)    Número seqencial de entrada do item da filial origem            OPERACIONAL                        NaN
PCUEPSSALDOENT   CODFILIALULTENT  VARCHAR2(2) Código da filial origem informado na tela para consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*