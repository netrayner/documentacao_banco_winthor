# 📊 Tabela: PCCARTACORRECAOC

### Estrutura de Colunas e Restrições

          Tabela                Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCARTACORRECAOC      NUMCARTACORRECAO NUMBER(10,0) Número Sequencial Identificador da Carta de Correção    CHAVE PRIMÁRIA (PK)                        NaN
PCCARTACORRECAOC          NUMTRANSACAO NUMBER(10,0)                   Número da Transação da Nota Fiscal            OPERACIONAL                        NaN
PCCARTACORRECAOC               ESPECIE  VARCHAR2(2)                          Espéci da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC             MOVIMENTO  VARCHAR2(1)                   Movimento da Nota Saída ou Entrada            OPERACIONAL                        NaN
PCCARTACORRECAOC     DATACARTACORRECAO         DATE                            Data da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC AMBIENTECARTACORRECAO  VARCHAR2(1)                        Ambienta da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC           SITUACAOCCE  NUMBER(5,0)                        Situação da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC              CHAVECCE VARCHAR2(65)                           Chave da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC          PROTOCOLOCCE VARCHAR2(20)                       Protocolo da Carta de Correção            OPERACIONAL                        NaN
PCCARTACORRECAOC    CODUSUARIOINCLUSAO  NUMBER(8,0)        Codigo do usuario que fez a carta de correção            OPERACIONAL                        NaN
PCCARTACORRECAOC   CODUSUARIOALTERACAO  NUMBER(8,0)    Codigo do usuario que alterou a carta de correção            OPERACIONAL                        NaN
PCCARTACORRECAOC       NUMEROSEQUENCIA  NUMBER(8,0)              Número de sequência de envio para sefaz            OPERACIONAL                        NaN
PCCARTACORRECAOC          ENVIADOEMAIL  VARCHAR2(1)                                    Enviado email Cce            OPERACIONAL                        NaN
PCCARTACORRECAOC               TIPODOC  NUMBER(1,0)                         Tipo documento NFE=0 e CTE=1            OPERACIONAL                        NaN
PCCARTACORRECAOC       VERSAOLAYOUTNFE  VARCHAR2(5)                 Versão do layout do arquivo na Sefaz            OPERACIONAL                        NaN
PCCARTACORRECAOC   CODIGONUMERICOCHAVE  VARCHAR2(8)                  Código númerico que compoem a chave            OPERACIONAL                        NaN
PCCARTACORRECAOC         TIPOIMPRESSAO  VARCHAR2(1)              Tipo de impressão (retrato ou paisagem)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*