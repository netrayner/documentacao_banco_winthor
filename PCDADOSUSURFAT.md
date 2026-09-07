# 📊 Tabela: PCDADOSUSURFAT

### Estrutura de Colunas e Restrições

        Tabela                   Coluna Tipo/Tamanho                                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDADOSUSURFAT                   NUMDOC NUMBER(10,0)                                                             Número do Documento    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSUSURFAT                  TIPODOC  VARCHAR2(1)                                                               Tipo do Documento    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSUSURFAT             CODMOTORISTA NUMBER(10,0)                                                             Código do Motorista            OPERACIONAL                        NaN
PCDADOSUSURFAT               CODVEICULO NUMBER(10,0)                                                               Código do Veículo            OPERACIONAL                        NaN
PCDADOSUSURFAT                   CODCOB  VARCHAR2(4)                                                              Código de Cobrança            OPERACIONAL                        NaN
PCDADOSUSURFAT                CODTRANSP NUMBER(10,0)                                                        Código da Transportadora            OPERACIONAL                        NaN
PCDADOSUSURFAT      CODTRANSPREDESPACHO NUMBER(10,0)                                            Código da Transportadora de Despacho            OPERACIONAL                        NaN
PCDADOSUSURFAT            CODCONFERENTE NUMBER(10,0)                                                            Código do Conferente            OPERACIONAL                        NaN
PCDADOSUSURFAT                GERARVALE  VARCHAR2(1)                                           Se é para gerar vale, 'S', Se não 'N'            OPERACIONAL                        NaN
PCDADOSUSURFAT                 PERCVALE  NUMBER(5,2)                                                 Percentual do Vale do Motorista            OPERACIONAL                        NaN
PCDADOSUSURFAT              CODHISTVALE NUMBER(10,0)                                        Código do Histórico do Vale do Motorista            OPERACIONAL                        NaN
PCDADOSUSURFAT             NUMCAIXAVALE NUMBER(10,0)                                            Número do Caixa do Vale do Motorista            OPERACIONAL                        NaN
PCDADOSUSURFAT          GERARNFTRANSFST  VARCHAR2(1)                  Se for gerar Nota fiscal de transferencia ST, 'S'. Se não, 'N'            OPERACIONAL                        NaN
PCDADOSUSURFAT     FRETEDESPACHOVIRTUAL  VARCHAR2(1)                      Se tiver frete Despacho da Filial Virtual, 'S'. Se não 'N'            OPERACIONAL                        NaN
PCDADOSUSURFAT   FRETEREDESPACHOVIRTUAL  VARCHAR2(1)                   Se tiver Frete Redespacho da Filial Virtual, 'S'. Se não, 'N'            OPERACIONAL                        NaN
PCDADOSUSURFAT   CODTRANSPFILIALVIRTUAL NUMBER(10,0)                                      Código da Transportadora da Filial Virtual            OPERACIONAL                        NaN
PCDADOSUSURFAT  CODVEICULOFILIALVIRTUAL NUMBER(10,0)                                             Código do Veículo da Filial Virtual            OPERACIONAL                        NaN
PCDADOSUSURFAT               CODCARRETA NUMBER(10,0)                                                               Código da Carreta            OPERACIONAL                        NaN
PCDADOSUSURFAT CODCARRETA2FILIALVIRTUAL NUMBER(22,0)                                              Código da Carreta 2 Filial Virtual            OPERACIONAL                        NaN
PCDADOSUSURFAT CODCARRETA1FILIALVIRTUAL NUMBER(22,0)                                              Código da Carreta 1 Filial Virtual            OPERACIONAL                        NaN
PCDADOSUSURFAT              DATAENTREGA         DATE                                                                 Data da Entrega            OPERACIONAL                        NaN
PCDADOSUSURFAT       MATRICULAFATURISTA NUMBER(22,0)                                                          Matricula do Faturista            OPERACIONAL                        NaN
PCDADOSUSURFAT                DATASAIDA         DATE                                                                   Data de Saida            OPERACIONAL                        NaN
PCDADOSUSURFAT     PODEFATURARAUTOMATIC  VARCHAR2(1) Faturar carregamento/pedido automaticamento ao fim do processo de transferência            OPERACIONAL                        NaN
PCDADOSUSURFAT            CODCOBVIRTUAL  VARCHAR2(4)                                        Código de Cobrança Transferência Virtual            OPERACIONAL                        NaN
PCDADOSUSURFAT      SITUACAOFATURAMENTO NUMBER(10,0)                                        Situação do Processamento de Faturamento            OPERACIONAL                        NaN
PCDADOSUSURFAT    DATAHORAPROCESSAMENTO         DATE                                             Data e Hora Do Último Processamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*