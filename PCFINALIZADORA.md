# 📊 Tabela: PCFINALIZADORA

### Estrutura de Colunas e Restrições

        Tabela              Coluna  Tipo/Tamanho                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFINALIZADORA     CODFINALIZADORA   NUMBER(4,0)                                     Codigo da Finalizadora.    CHAVE PRIMÁRIA (PK)                        NaN
PCFINALIZADORA           DESCRICAO VARCHAR2(100)                                  Descrição da Finalizadora.            OPERACIONAL                        NaN
PCFINALIZADORA            CODPLPAG   NUMBER(4,0)                               Codigo do Plano de Pagamento.            OPERACIONAL                        NaN
PCFINALIZADORA              CODCOB   VARCHAR2(4)                                         Codigo da Cobrança.            OPERACIONAL                        NaN
PCFINALIZADORA            VLMINIMO  NUMBER(15,2)                                              Valor Minimo .            OPERACIONAL                        NaN
PCFINALIZADORA            VLMAXIMO  NUMBER(15,2)                                               Valor Maximo.            OPERACIONAL                        NaN
PCFINALIZADORA    IMPRIMEVINCULADO   VARCHAR2(1)                                          Imprime Vinculado.            OPERACIONAL                        NaN
PCFINALIZADORA             NUMVIAS   NUMBER(3,0)                           Numero de Vias a serem impressas.            OPERACIONAL                        NaN
PCFINALIZADORA             ESPECIE   VARCHAR2(6)                                                   Especie .            OPERACIONAL                        NaN
PCFINALIZADORA      VERIFICALIMITE   VARCHAR2(1)                                           Verificar Limite.            OPERACIONAL                        NaN
PCFINALIZADORA      AUTORIZALIMITE   VARCHAR2(1)                                           Autorizar Limite.            OPERACIONAL                        NaN
PCFINALIZADORA             LERCMC7   VARCHAR2(1)                        Ler CMC7(Tarja Magnetica do cheque).            OPERACIONAL                        NaN
PCFINALIZADORA     PERMITEDESCONTO   VARCHAR2(1)                                           Permite Desconto.            OPERACIONAL                        NaN
PCFINALIZADORA           CODFILIAL   VARCHAR2(2)                                            Código da Filial            OPERACIONAL                        NaN
PCFINALIZADORA        PERMITETROCO   VARCHAR2(1)                             Permitir efetuar troco na venda            OPERACIONAL                        NaN
PCFINALIZADORA PERMITEPARCELAMENTO   VARCHAR2(1)                                  Permite parcelar pagamento            OPERACIONAL                        NaN
PCFINALIZADORA  VALORMINIMOPARCELA  NUMBER(18,2)                                    Valor mínimo por parcela            OPERACIONAL                        NaN
PCFINALIZADORA     SOLICITACLIENTE   VARCHAR2(1)                         Cliente deve ser informado na venda            OPERACIONAL                        NaN
PCFINALIZADORA      USACOMOENTRADA   VARCHAR2(1)                                            Usa como entrada            OPERACIONAL                        NaN
PCFINALIZADORA CONSULTACHEQUESITEF   VARCHAR2(1)                      Indicação de uso de consulta de cheque            OPERACIONAL                        NaN
PCFINALIZADORA        DTINATIVACAO          DATE                                          Data da Inativação            OPERACIONAL                        NaN
PCFINALIZADORA   CODFUNCINATIVACAO  NUMBER(10,0)                           Funcionário que inativou cadastro            OPERACIONAL                        NaN
PCFINALIZADORA       QTMAXPARCELAS   NUMBER(4,0)                               Quantidade Máxima de parcelas            OPERACIONAL                        NaN
PCFINALIZADORA            PERTXFIN   NUMBER(8,4)       Valor para definir acréscimo/desconto da finalizadora            OPERACIONAL                        NaN
PCFINALIZADORA    PARCELAMENTOLOJA   VARCHAR2(1)       Identifica se o parcelamento será realizado pela loja            OPERACIONAL                        NaN
PCFINALIZADORA           TIPOJUROS   VARCHAR2(1)        Identifica se o Juros sera simples(S) ou composto(C)            OPERACIONAL                        NaN
PCFINALIZADORA  PARCELAINICIOJUROS   NUMBER(2,0)                 A partir de qual parcela será cobrado Juros            OPERACIONAL                        NaN
PCFINALIZADORA CODFILIALINTEGRACAO   NUMBER(3,0)                              Código da Filial de Integração            OPERACIONAL                        NaN
PCFINALIZADORA    CODCOBINTEGRACAO   VARCHAR2(4)           Código de cobrança para integração Consinco (TEF)            OPERACIONAL                        NaN
PCFINALIZADORA  CODPLPAGINTEGRACAO   NUMBER(4,0) Código de plano de pagamento para integração Consinco (TEF)            OPERACIONAL                        NaN
PCFINALIZADORA          DTULTALTER          DATE                           Data da ultima alteracao do campo            OPERACIONAL                        NaN
PCFINALIZADORA           DTALTERC5  TIMESTAMP(6)                                              Data alteracao            OPERACIONAL                        NaN
PCFINALIZADORA        NUMBINCARTAO   VARCHAR2(9)                                     Numero do BIN de Cartão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*