# 📊 Tabela: PCLOGCESSAOCREDITO

### Estrutura de Colunas e Restrições

            Tabela      Coluna  Tipo/Tamanho                                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGCESSAOCREDITO NOSSONUMERO  VARCHAR2(30)                                 Valor do campo "8 - Seu Número" (posição 48 a 72) do registro detalhe (filial+numtransvenda+prest)            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO      DUPLIC  NUMBER(10,0)    Valor do campo "4 - Núm. do Contrato" (posição 18 a 29) do registro detalhe, referente ao número da duplicata (PCPREST.DUPLIC).            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO       PREST   VARCHAR2(2)     Valor do campo "5 - Número da Parcela" (posição 30 a 32) do registro detalhe, referente ao número da prestação (PCPREST.PREST)            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO   CODFILIAL   VARCHAR2(2)                                                                 Valor extraído do campo NOSSONUMERO referente ao código da filial.            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO      ACEITE   VARCHAR2(1) Valor do campo "19 - Identificação da Ocorrência" (posição 139 a 140) do registro detalhe, sendo S para valor 02 e N para valor 03            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO CODMENSAGEM   NUMBER(4,0)                                                                                                          Código da mensagem do log            OPERACIONAL                        NaN
PCLOGCESSAOCREDITO    MENSAGEM VARCHAR2(200)                                                                                                       Descrição da mensagem do log            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*