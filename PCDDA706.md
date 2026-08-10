# 📊 Tabela: PCDDA706

### Estrutura de Colunas e Restrições

  Tabela                       Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDDA706                 RECNUMPCLANC  NUMBER(10,0)               RELACIONAMENTO COM PCLANC            OPERACIONAL                        NaN
PCDDA706              NUMBANCOARQUIVO   NUMBER(4,0)          NUMERO DO BANCO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706                   CGCARQUIVO  VARCHAR2(18)                  CGC/CPF NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706                 VALORARQUIVO  NUMBER(12,2)                    VALOR NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706                DTVENCARQUIVO          DATE       DATA DE VENCIMENTO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706               NUMNOTAARQUIVO  NUMBER(15,0)           NUMERO DA NOTA NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706              CODBARRAARQUIVO  VARCHAR2(44)            CODIGO BARRAS NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706              PARCEIROARQUIVO VARCHAR2(100)                 PARCEIRO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706             ARQUIVOIMPORTADO VARCHAR2(100)               NOME DO ARQUIVO IMPORTADO            OPERACIONAL                        NaN
PCDDA706               DATAIMPORTACAO          DATE           DATA DA IMPORTACAO DO ARQUIVO            OPERACIONAL                        NaN
PCDDA706            DATAPROCESSAMENTO          DATE        DATA DO PROCESSAMENTO COM PCLANC            OPERACIONAL                        NaN
PCDDA706            CODFUNCIMPORTACAO   NUMBER(8,0)   FUNCIONARIO QUE IMPORTOU OS REGISTROS            OPERACIONAL                        NaN
PCDDA706                     EXCLUIDA   VARCHAR2(1) SE FOI EXCLUIDA PELO USUARIO VIA ROTINA            OPERACIONAL                        NaN
PCDDA706               SITUACAOBOLETO   VARCHAR2(2)            STATUS DA SITUAÇÃO DO BOLETO            OPERACIONAL                        NaN
PCDDA706    CGCARQUIVOSACADORAVALISTA  VARCHAR2(18)     CGC SACADOR AVALISTA DO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706       SACADORAVALISTAARQUIVO VARCHAR2(100)         SACADOR AVALISTA DO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706       NUMNOTACOMPLETOARQUIVO  VARCHAR2(15)  NUMERO DA NOTA COMPLETO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706       AGENCIAPARCEIROARQUIVO  VARCHAR2(10)      AGENCIA DO PARCEIRO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706 CONTACORRENTEPARCEIROARQUIVO  VARCHAR2(10)  CONTA CORRENTE PARCEIRO NO ARQUIVO DDA            OPERACIONAL                        NaN
PCDDA706                    CGCFILIAL  VARCHAR2(14)                           CGC DA FILIAL            OPERACIONAL                        NaN
PCDDA706               DATAGERARQUIVO          DATE                 DATA GERACAO DO ARQUIVO            OPERACIONAL                        NaN
PCDDA706       VALORABATIMENTOARQUIVO  NUMBER(14,2)        VALOR ABATIMENTO NO ARQUIVO DDDA            OPERACIONAL                        NaN
PCDDA706             DATAGERARARQUIVO          DATE              Data da Geração do Arquivo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*