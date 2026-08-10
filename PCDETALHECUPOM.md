# 📊 Tabela: PCDETALHECUPOM

### Estrutura de Colunas e Restrições

        Tabela           Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDETALHECUPOM        CODFILIAL  VARCHAR2(2)               Cdigo da filial.            OPERACIONAL                        NaN
PCDETALHECUPOM         NUMCAIXA  NUMBER(4,0)               Número do caixa.            OPERACIONAL                        NaN
PCDETALHECUPOM   NUMCAIXAFISCAL  NUMBER(4,0)                 número do ecf.            OPERACIONAL                        NaN
PCDETALHECUPOM              COO  NUMBER(6,0) contador de ordem de operação.            OPERACIONAL                        NaN
PCDETALHECUPOM              CCF  NUMBER(6,0)      contador de cupom fiscal.            OPERACIONAL                        NaN
PCDETALHECUPOM              GNF  NUMBER(6,0)     contador geral não fiscal.            OPERACIONAL                        NaN
PCDETALHECUPOM           CODCOB  VARCHAR2(4)            código de cobrança.            OPERACIONAL                        NaN
PCDETALHECUPOM        VALORPAGO NUMBER(12,2)                    valor pago.            OPERACIONAL                        NaN
PCDETALHECUPOM INDICADORESTORNO  VARCHAR2(1)          indicador de estorno.            OPERACIONAL                        NaN
PCDETALHECUPOM     VALORESTORNO NUMBER(12,2)              valor do estorno.            OPERACIONAL                        NaN
PCDETALHECUPOM         EXPORTOU  VARCHAR2(1)                     exportado.            OPERACIONAL                        NaN
PCDETALHECUPOM             TIPO  VARCHAR2(1) Tipo de sangria ou suprimento.            OPERACIONAL                        NaN
PCDETALHECUPOM             DATA         DATE            Data do lançamento.            OPERACIONAL                        NaN
PCDETALHECUPOM        IMPORTADO  VARCHAR2(1)        Importado [S]sim [N]não            OPERACIONAL                        NaN
PCDETALHECUPOM         CODBANCO  NUMBER(4,0)               Código do banco.            OPERACIONAL                        NaN
PCDETALHECUPOM          CODFUNC  NUMBER(8,0)          Código do funcionario            OPERACIONAL                        NaN
PCDETALHECUPOM       ROTINALANC VARCHAR2(48) ROTINA QUE GRAVOU A INFORMACAO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*