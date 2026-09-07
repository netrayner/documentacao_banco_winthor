# 📊 Tabela: PCLOGERROWMSAUTOMATICO

### Estrutura de Colunas e Restrições

                Tabela          Coluna  Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGERROWMSAUTOMATICO       CODFILIAL   VARCHAR2(2)                 Filial de processamento            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO          NUMPED  NUMBER(10,0)       Número do pedido a ser processado            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO          NUMCAR   NUMBER(8,0) Número do carregamento a ser processado            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO      NUMNOTAENT  NUMBER(10,0)             NF entrada a ser processada            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO     NUMTRANSENT  NUMBER(10,0)         Trans. Entrada a ser processada            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO    NUMNOTASAIDA  NUMBER(10,0)               NF saída a ser processada            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO   NUMTRANSVENDA  NUMBER(10,0)           Trans. Saída a ser processada            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO         CODPROD   NUMBER(6,0)                       Código do produto            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO          MOTIVO VARCHAR2(500)         Motivo do erro de processamento            OPERACIONAL                        NaN
PCLOGERROWMSAUTOMATICO DTPROCESSAMENTO          DATE                   Data de processamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*