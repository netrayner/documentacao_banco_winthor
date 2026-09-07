# 📊 Tabela: PCMOVTRANSF

### Estrutura de Colunas e Restrições

     Tabela                    Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVTRANSF                    CODIGO  NUMBER(10,0)                                  Código sequencial do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVTRANSF                    NUMPED  NUMBER(10,0)                                               Numero do Pedido            OPERACIONAL                        NaN
PCMOVTRANSF             NUMTRANSVENDA  NUMBER(10,0)                                      Numero Transação de Venda            OPERACIONAL                        NaN
PCMOVTRANSF               NUMTRANSENT  NUMBER(10,0)                                    Numero Transação de Entrada            OPERACIONAL                        NaN
PCMOVTRANSF                    NUMCAR  NUMBER(10,0)                                         Numero do Carregamento            OPERACIONAL                        NaN
PCMOVTRANSF            ROTINAGERADORA  VARCHAR2(48)                                                Rotina geradora            OPERACIONAL                        NaN
PCMOVTRANSF              ROTINAULTALT  VARCHAR2(48)                                        Rotina Ultima Alteração            OPERACIONAL                        NaN
PCMOVTRANSF                   CODUSUR   NUMBER(4,0)                                              Código do Usuário            OPERACIONAL                        NaN
PCMOVTRANSF                 CODFILIAL   VARCHAR2(2)                                               Código da Filial            OPERACIONAL                        NaN
PCMOVTRANSF           CODFILIALRETIRA   VARCHAR2(2)                                        Codigo da Filial Retira            OPERACIONAL                        NaN
PCMOVTRANSF               CODFILIALNF   VARCHAR2(2)                                            Codigo da Filial NF            OPERACIONAL                        NaN
PCMOVTRANSF             VERSAOSERVICO  VARCHAR2(48)                                              Versão do Serviço            OPERACIONAL                        NaN
PCMOVTRANSF            DTCANCELAMENTO          DATE                                           Data do Cancelamento            OPERACIONAL                        NaN
PCMOVTRANSF              TIPOOPERACAO VARCHAR2(100)                              Tipo da Operação de Transferência            OPERACIONAL                        NaN
PCMOVTRANSF              NUMTRANSACAO  NUMBER(10,0)                                            Número de Transação            OPERACIONAL                        NaN
PCMOVTRANSF        NUMTRANSACAOORIGEM  NUMBER(10,0)                                  Número de Transação de Origem            OPERACIONAL                        NaN
PCMOVTRANSF           CODFILIALORIGEM   VARCHAR2(2)                                        Código Filial de Origem            OPERACIONAL                        NaN
PCMOVTRANSF    NUMTRANSACAOREFERENCIA  NUMBER(10,0)                              Número de Transação de Referência            OPERACIONAL                        NaN
PCMOVTRANSF    TIPOOPERACAOREFERENCIA VARCHAR2(100)                                  Tipo de Operação De Refeência            OPERACIONAL                        NaN
PCMOVTRANSF               DTDEVOLUCAO          DATE                             Data de Devolução da Transferência            OPERACIONAL                        NaN
PCMOVTRANSF NUMTRANSACAOCONTRAPARTIDA  NUMBER(10,0)                 Numero Transação de Contrapartida na Devolução            OPERACIONAL                        NaN
PCMOVTRANSF TIPOOPERACAOCONTRAPARTIDA VARCHAR2(100)                                    Tipo Operação Contrapartida            OPERACIONAL                        NaN
PCMOVTRANSF NUMTRANSACAODEVOLUCAOCANC  NUMBER(10,0)                        Numero Transação de Devolução Cancelada            OPERACIONAL                        NaN
PCMOVTRANSF TIPOOPERACAODEVOLUCAOCANC VARCHAR2(100)                              Tipo Operação Devolução Cancelada            OPERACIONAL                        NaN
PCMOVTRANSF         SITUACAOGERACAONF VARCHAR2(100)                             Situação de Geração de Nota Fiscal            OPERACIONAL                        NaN
PCMOVTRANSF     SITUACAOPROCESSAMENTO   VARCHAR2(1)                Situação Processamento da Nota de Transferência            OPERACIONAL                        NaN
PCMOVTRANSF          TENTATIVAGERACAO   NUMBER(4,0)                             Nro Tentativa de Gerar Nota Fiscal            OPERACIONAL                        NaN
PCMOVTRANSF          TENTATIVAENTRADA   NUMBER(4,0)                              Nro Tentativa de Realizar Entrada            OPERACIONAL                        NaN
PCMOVTRANSF  DATAHORATENTATIVAGERACAO          DATE                Data e Hora da Última Tentativa de Gerar a Nota            OPERACIONAL                        NaN
PCMOVTRANSF  DATAHORATENTATIVAENTRADA          DATE          Data e Hora da Última Tentativa de Realizar a Entrada            OPERACIONAL                        NaN
PCMOVTRANSF    SITUACAOCANCELAMENTONF VARCHAR2(100)                              Situação Cancelamento Nota Fiscal            OPERACIONAL                        NaN
PCMOVTRANSF     TENTATIVACANCELAMENTO   NUMBER(4,0)                          Nro Tentativa de Cancelar Nota Fiscal            OPERACIONAL                        NaN
PCMOVTRANSF DATAHORATENTATIVACANCELAR          DATE                    Data e Hora da Última Tentativa de Cancelar            OPERACIONAL                        NaN
PCMOVTRANSF        MOTIVOCANCELAMENTO VARCHAR2(120)                                         Motivo de Cancelamento            OPERACIONAL                        NaN
PCMOVTRANSF     MATRICULACANCELAMENTO   NUMBER(8,0)                                 Matrículo Usuário Cancelamento            OPERACIONAL                        NaN
PCMOVTRANSF     DATAHORAPROCESSAMENTO          DATE                                   Data Hora Processamento Nota            OPERACIONAL                        NaN
PCMOVTRANSF     NUMTRANSACAOPRINCIPAL  NUMBER(10,0)         Transação Principal na Quebra de Nota de Transferência            OPERACIONAL                        NaN
PCMOVTRANSF     TIPOOPERACAOPRINCIPAL VARCHAR2(100) Tipo da Transação Principal na Quebra de Nota de Transferência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*