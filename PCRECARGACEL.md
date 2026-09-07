# 📊 Tabela: PCRECARGACEL

### Estrutura de Colunas e Restrições

      Tabela             Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECARGACEL               DATA         DATE                                 Data da recarga.            OPERACIONAL                        NaN
PCRECARGACEL          CODFUNCCX  NUMBER(8,0)                     Código Funcionário do Caixa.            OPERACIONAL                        NaN
PCRECARGACEL           NUMCAIXA  NUMBER(4,0)                                 Número do Caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECARGACEL      NUMSERIEEQUIP VARCHAR2(30)                          Número de Série do ECF.            OPERACIONAL                        NaN
PCRECARGACEL           NUMCUPOM NUMBER(10,0)      Número do comprovante gerencial de recarga.            OPERACIONAL                        NaN
PCRECARGACEL                NSU  NUMBER(6,0) Número Sequencial Único da Transação de Recarga.            OPERACIONAL                        NaN
PCRECARGACEL          OPERADORA VARCHAR2(15)                 Operadora de Recarga de Celular.            OPERACIONAL                        NaN
PCRECARGACEL              VALOR NUMBER(12,2)                                Valor da Recarga.            OPERACIONAL                        NaN
PCRECARGACEL          NUMPEDECF NUMBER(10,0)                       Número do Pedido do Caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCRECARGACEL      NUMTRANSVENDA NUMBER(10,0)                    Número da Transação de Venda.            OPERACIONAL                        NaN
PCRECARGACEL          EXPORTADO  VARCHAR2(1)                        Exportação para Servidor.            OPERACIONAL                        NaN
PCRECARGACEL       DTEXPORTACAO         DATE              Data de Exportação para o Servidor.            OPERACIONAL                        NaN
PCRECARGACEL          CODFILIAL  VARCHAR2(2)                       Indica o código da filial.            OPERACIONAL                        NaN
PCRECARGACEL             RECNUM  NUMBER(8,0)    Código de reçacionamento com a tabela PCLANC.            OPERACIONAL                        NaN
PCRECARGACEL  CODOPERRECARGACEL NUMBER(14,0)         Filial/Regional da operadora de celular.            OPERACIONAL                        NaN
PCRECARGACEL       TIPOOPERACAO  VARCHAR2(1)                                 Tipo de operação            OPERACIONAL                        NaN
PCRECARGACEL         INFPRODUTO VARCHAR2(40)                            Informação do produto            OPERACIONAL                        NaN
PCRECARGACEL NUMFECHAMENTOMOVCX NUMBER(10,0)                             Numero de fechamento            OPERACIONAL                        NaN
PCRECARGACEL      DTMOVIMENTOCX         DATE                               Data de fechamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*