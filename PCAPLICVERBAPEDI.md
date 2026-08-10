# 📊 Tabela: PCAPLICVERBAPEDI

### Estrutura de Colunas e Restrições

          Tabela           Coluna Tipo/Tamanho                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPLICVERBAPEDI         NUMVERBA  NUMBER(6,0)                                  Número da verba utilizado na aplicação.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI             DATA         DATE                                                Data e hora da aplicação.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI         NUMAPLIC NUMBER(18,6)                                                     Número da aplicação.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAPEDI          CODPROD  NUMBER(6,0)                                Código do produto utilizado na aplicação.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAPEDI        NUMSEQPED  NUMBER(6,0) Número de seqüência do item no pedido(caso seja o mesmo item no pedido).    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAPEDI       VLVERBACMV NUMBER(18,6)                               Valor utilizado na  aplicação rebaixa CMV.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI           NUMPED NUMBER(10,0)                        Número do pedido de venda utilizado na aplicação.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPLICVERBAPEDI        CODFILIAL  VARCHAR2(2)                                 Código da filial utilizado na aplicação.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI       ROTINALANC  NUMBER(6,0)                                 Código da rotina utilizado na aplicação.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI          CODFUNC  NUMBER(8,0)                              Código do usuário que executou a aplicação.            OPERACIONAL                        NaN
PCAPLICVERBAPEDI    VLCUSTOFINANT NUMBER(18,6)                                 Valor do custo financeiro anterior (CMV)            OPERACIONAL                        NaN
PCAPLICVERBAPEDI   VLCUSTOREALANT NUMBER(18,6)                                       Valor do custo real anterior (CMV)            OPERACIONAL                        NaN
PCAPLICVERBAPEDI     CODPRODPRINC  NUMBER(9,0)                                             CÃ³digo do produto principal            OPERACIONAL                        NaN
PCAPLICVERBAPEDI ROTINALANCVERSAO VARCHAR2(32)                                                Gravar a rotina e versÃ£o            OPERACIONAL                        NaN
PCAPLICVERBAPEDI           QTITEM NUMBER(20,6)                                             Quantidade do item rebaixado            OPERACIONAL                        NaN
PCAPLICVERBAPEDI   QTTOTALREBAIXA NUMBER(20,6)                            Quantidade total da familia do item rebaixado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*