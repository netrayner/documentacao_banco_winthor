# 📊 Tabela: PCWMSOUTPUTDET

### Estrutura de Colunas e Restrições

        Tabela          Coluna Tipo/Tamanho       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWMSOUTPUTDET            TIPO      CHAR(1)         Tipo do documento            OPERACIONAL                        NaN
PCWMSOUTPUTDET          NUMERO NUMBER(10,0)       Número do documento            OPERACIONAL                        NaN
PCWMSOUTPUTDET         CODPROD  NUMBER(6,0)         Código do produto            OPERACIONAL                        NaN
PCWMSOUTPUTDET          CODCLI  NUMBER(6,0)         Código do cliente            OPERACIONAL                        NaN
PCWMSOUTPUTDET       CODFORNEC  NUMBER(6,0)      Código do fornecedor            OPERACIONAL                        NaN
PCWMSOUTPUTDET       CODFILIAL  VARCHAR2(2)          Código da filial            OPERACIONAL                        NaN
PCWMSOUTPUTDET      QTSEPARADA NUMBER(20,6)       Quantidade separada            OPERACIONAL                        NaN
PCWMSOUTPUTDET      QTRECEBIDA NUMBER(20,6)       Quantidade recebida            OPERACIONAL                        NaN
PCWMSOUTPUTDET        QTAVARIA NUMBER(20,6)       Quantidade avariada            OPERACIONAL                        NaN
PCWMSOUTPUTDET         QTCORTE NUMBER(20,6)        Quantidade cortada            OPERACIONAL                        NaN
PCWMSOUTPUTDET       DTEMISSAO         DATE           Data da emissão            OPERACIONAL                        NaN
PCWMSOUTPUTDET        SEMAFORO  NUMBER(2,0)        Status do registro            OPERACIONAL                        NaN
PCWMSOUTPUTDET DTPROCESSAMENTO         DATE Data último processamento            OPERACIONAL                        NaN
PCWMSOUTPUTDET         NUMLOTE VARCHAR2(20)            Número do lote            OPERACIONAL                        NaN
PCWMSOUTPUTDET           NUMOS NUMBER(10,0)            Número da o.s.            OPERACIONAL                        NaN
PCWMSOUTPUTDET       NUMPALETE  NUMBER(6,0)          Número do palete            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*