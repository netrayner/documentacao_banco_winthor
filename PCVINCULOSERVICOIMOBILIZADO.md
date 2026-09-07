# 📊 Tabela: PCVINCULOSERVICOIMOBILIZADO

### Estrutura de Colunas e Restrições

                     Tabela             Coluna Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOSERVICOIMOBILIZADO          CODFILIAL  VARCHAR2(2)                                                           Código da filial da operação.            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO          CODFORNEC  NUMBER(6,0)                                                       Código do fornecedor da operação.            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO  CODLOCALIZACAOBEM  NUMBER(6,0)                                                           Código de localização do bem.            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO     CODPRODIMOBPRI  NUMBER(6,0)                                                 Código do produto imobilizado principal            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO  CODRESPONSAVELBEM  NUMBER(8,0)                                                               Código responsável do bem            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO          DTENTRADA         DATE                                                                         Data da Entrada            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO           DTCANCEL         DATE                                                                    Data de Cancelamento            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO            NUMNOTA NUMBER(10,0)                                                                          Número da Nota            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO       NUMTRANSACAO NUMBER(10,0)                                                                     Número da transação            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO      TIPOTRANSACAO  VARCHAR2(2)                                                                       Tipo da Transação            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO            CODPROD  NUMBER(6,0)      Código do produto, neste caso, pode ser considerado também como código do serviço.            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO           DESCPROD VARCHAR2(45) Descrição do produto, neste caso, poe ser considerado também como descrição do serviço.            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO          VLSERVICO NUMBER(22,2)                                                                        Valor do serviço            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO      PERCVINCULADO NUMBER(12,4)                                                                    Percentual vinculado            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO             CODBEM  NUMBER(6,0)                                                                           Código do Bem            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO            DESCBEM VARCHAR2(45)                                                                        Descrição do Bem            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO          SEQUENCIA NUMBER(10,0)                                                                        Sequencia do bem            OPERACIONAL                        NaN
PCVINCULOSERVICOIMOBILIZADO VLSERVICOUTILIZADO NUMBER(22,2)                                                      Valor do serviço que foi útilizado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*