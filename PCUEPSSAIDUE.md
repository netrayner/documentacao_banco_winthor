# 📊 Tabela: PCUEPSSAIDUE

### Estrutura de Colunas e Restrições

      Tabela            Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUEPSSAIDUE         CODFILIAL  VARCHAR2(2)                                        Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSAIDUE       NUMTRANSENT NUMBER(10,0)                          Número de Transação da entrada    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSAIDUE             DTENT         DATE                                 Data da nota de entrada            OPERACIONAL                        NaN
PCUEPSSAIDUE     NUMTRANSVENDA NUMBER(10,0)                            Número de Transação da saída    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSAIDUE           DTSAIDA         DATE                             Data da transação de saida             OPERACIONAL                        NaN
PCUEPSSAIDUE           CODPROD  NUMBER(6,0)                                       Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCUEPSSAIDUE    CHAVENFEULTENT VARCHAR2(44)            Chave da nfe da última entrada filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE NUMTRANSENTULTENT NUMBER(10,0)     Número da transação da última entrada filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE       NUMNFULTENT NUMBER(10,0)          Número da nota da última entrada filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE   CODFORNECULTENT  NUMBER(6,0)            Código do fornecedor da última filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE       SERIEULTENT  VARCHAR2(3)                   Série da nota da última filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE   NUMSEQENTULTENT  NUMBER(5,0)    Número seqencial de entrada do item da filial origem            OPERACIONAL                        NaN
PCUEPSSAIDUE   CODFILIALULTENT  VARCHAR2(2) Código da filial origem informado na tela para consulta            OPERACIONAL                        NaN
PCUEPSSAIDUE            NUMSEQ NUMBER(20,0)       Campo para replicar o numseq das notas de entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*