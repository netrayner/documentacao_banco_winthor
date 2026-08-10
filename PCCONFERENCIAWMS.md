# 📊 Tabela: PCCONFERENCIAWMS

### Estrutura de Colunas e Restrições

          Tabela          Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFERENCIAWMS          NUMSEQ NUMBER(10,0)                      Indica o número de sequencia    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFERENCIAWMS           NUMOS NUMBER(10,0)                          Indicaa ordem de serviço            OPERACIONAL                        NaN
PCCONFERENCIAWMS     NUMTRANSWMS NUMBER(10,0)                            Indica a transação WMS            OPERACIONAL                        NaN
PCCONFERENCIAWMS         CODPROD  NUMBER(6,0)                        Indica o código do Produto            OPERACIONAL                        NaN
PCCONFERENCIAWMS              QT NUMBER(20,8)                               Indica a quantidade            OPERACIONAL                        NaN
PCCONFERENCIAWMS     QTCONFERIDA NUMBER(20,8)                     Indica a quantidade conferida            OPERACIONAL                        NaN
PCCONFERENCIAWMS TIPOCONFERENCIA  VARCHAR2(2)                      Indica o tipo de conferencia            OPERACIONAL                        NaN
PCCONFERENCIAWMS        DTINICIO         DATE                              Indica a data Inicio            OPERACIONAL                        NaN
PCCONFERENCIAWMS           DTFIM         DATE                               Indica a data final            OPERACIONAL                        NaN
PCCONFERENCIAWMS     CODFUNCCONF  NUMBER(8,0)                    Indica o codigo do funcionário            OPERACIONAL                        NaN
PCCONFERENCIAWMS          NUMCAR  NUMBER(8,0)                   Indica o numero do carregamento            OPERACIONAL                        NaN
PCCONFERENCIAWMS          NUMPED NUMBER(10,0)                         Indica o numero do pedido            OPERACIONAL                        NaN
PCCONFERENCIAWMS        SEMAFORO  NUMBER(1,0)              Indica a identificação de integração            OPERACIONAL                        NaN
PCCONFERENCIAWMS       CODROTINA  NUMBER(6,0)                        Indica o código da rotina.            OPERACIONAL                        NaN
PCCONFERENCIAWMS      CODDISTRIB  VARCHAR2(4) Código da distribuição do carregamento conferido.            OPERACIONAL                        NaN
PCCONFERENCIAWMS   NUMTRANSVENDA NUMBER(10,0)                      Número da transação de venda            OPERACIONAL                        NaN
PCCONFERENCIAWMS          NUMVOL  NUMBER(6,0)                                  Número da volume            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*