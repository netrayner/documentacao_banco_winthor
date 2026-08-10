# 📊 Tabela: PCREGRACONTABIL

### Estrutura de Colunas e Restrições

         Tabela                        Coluna   Tipo/Tamanho                                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREGRACONTABIL                      CODREGRA   NUMBER(10,0)                                                                                      Indica o código controle.    CHAVE PRIMÁRIA (PK)                        NaN
PCREGRACONTABIL                     CODFILIAL    VARCHAR2(2)                                                                                     Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCREGRACONTABIL                DESCRICAOREGRA   VARCHAR2(60)                                                                                   Indica a descrição da regra.            OPERACIONAL                        NaN
PCREGRACONTABIL                  CODHISTORICO    NUMBER(4,0)                                                                                  Indica o código do histórico.            OPERACIONAL                        NaN
PCREGRACONTABIL                HISTCOMPLREGRA  VARCHAR2(200)                                                                             Indica o complemento do histórico.            OPERACIONAL                        NaN
PCREGRACONTABIL                CODFATOGERADOR    NUMBER(3,0)                                                                                  Indica o código fato gerador.            OPERACIONAL                        NaN
PCREGRACONTABIL                         ATIVO    VARCHAR2(1)                                                                                Indica se ativa a regra ou não.            OPERACIONAL                        NaN
PCREGRACONTABIL             DIACONTABILIZACAO    VARCHAR2(1)                                                                                Indica o dia da contabilização.            OPERACIONAL                        NaN
PCREGRACONTABIL                     DOCUMENTO   VARCHAR2(40)                                                          Indica o documento referente á movimentação contábil.            OPERACIONAL                        NaN
PCREGRACONTABIL              AGRUPAMENTOREGRA   VARCHAR2(20)                                                                             Indica como a regra será agrupada.            OPERACIONAL                        NaN
PCREGRACONTABIL         FORMADTCONTABILIZACAO    VARCHAR2(1)                                                                      Indica a forma da data da contabilização.            OPERACIONAL                        NaN
PCREGRACONTABIL                 CODPLANOCONTA    NUMBER(5,0)                                                                            Indica o código do plano de contas.            OPERACIONAL                        NaN
PCREGRACONTABIL            CONTABILIZAESTORNO    VARCHAR2(1)                                                       Informa se contabiliza os estornos de pagamentos ou não.            OPERACIONAL                        NaN
PCREGRACONTABIL                    OBSERVACAO           CLOB                                                                              Observação sobre a regra contábil            OPERACIONAL                        NaN
PCREGRACONTABIL          CODCONTASINTETICARCA   VARCHAR2(20)                                                                      Código da Conta Contábil Sintética do RCA            OPERACIONAL                        NaN
PCREGRACONTABIL           BUSCARDADOSPELADATA    VARCHAR2(1)                         Define qual campo de data será utilizado para a busca dos dados da integração contábil            OPERACIONAL                        NaN
PCREGRACONTABIL          TIPOCUSTO_MOVESTOQUE    VARCHAR2(1)                                                                       Tipo do custo da movimentação de estoque            OPERACIONAL                        NaN
PCREGRACONTABIL        CONDVENDA14_MOVESTOQUE    VARCHAR2(1)                                                                               16 - Considerar NF de saída TV14            OPERACIONAL                        NaN
PCREGRACONTABIL            CONSIDERARPROVISAO    VARCHAR2(1)                                                                 Define se regra considera ou não as provisões.            OPERACIONAL                        NaN
PCREGRACONTABIL       USAPRC_CONTROLEPRODUCAO    VARCHAR2(1) Campo usado na rotina 2130 pelo fato gerador 8, para resolver problemas de desempenho e alguns bancos de dados            OPERACIONAL                        NaN
PCREGRACONTABIL              BUSCAPORFILIALNF    VARCHAR2(1)       Campo definido pela 2129 e usado pela 2130 nos fatos geradores 1 e 10 definir a forma de busca da filial            OPERACIONAL                        NaN
PCREGRACONTABIL          GERARCENTROCUSTO_631    VARCHAR2(1)                                                                                                            NaN            OPERACIONAL                        NaN
PCREGRACONTABIL           USACONTATRANSITORIA    VARCHAR2(1)                          Campo responsável por habilitar o processo de conta transitória para o fato gerador 3            OPERACIONAL                        NaN
PCREGRACONTABIL              CONSDVENDA_TIPO8    VARCHAR2(1)                                       Opção de contabilizar o custo das notas tipo 8  - Remessa entrega futura            OPERACIONAL                        NaN
PCREGRACONTABIL          CONSIDERARCUSTOBONIF    VARCHAR2(1)                                                                  20 - Considerar custo para entrada bonificada            OPERACIONAL                        NaN
PCREGRACONTABIL          DESCONS_CUSTO_DEVCLI    VARCHAR2(1)                                                       21 - Desconsiderar custo para NF de devolução de cliente            OPERACIONAL                        NaN
PCREGRACONTABIL BAIXA_ADIANTFOR_MOV_NUMERARIO    VARCHAR2(1)                                          Considerar baixa de adiantamento de fornecedor movimentando numerario            OPERACIONAL                        NaN
PCREGRACONTABIL         DEVFORNECCONTACLIENTE    VARCHAR2(1)                                             Título de devolução de fornecedor contabilizar na conta do cliente            OPERACIONAL                        NaN
PCREGRACONTABIL      CONTABILIZACENTRORECEITA    VARCHAR2(1)                                                          Informar se a partida contabilizará centro de receita            OPERACIONAL                        NaN
PCREGRACONTABIL           CONS_ENT_SAIDA_CANC    VARCHAR2(1)                                                       09 - Considerar entrada e saídas de produções canceladas            OPERACIONAL                        NaN
PCREGRACONTABIL             DESC_CUSTO_NF_ENT    VARCHAR2(1)                                                          22 - Desconsiderar custo para NF de entrada cancelada            OPERACIONAL                        NaN
PCREGRACONTABIL              DESC_TIPOMERC_BD    VARCHAR2(1)                                                           08 - Desconsiderar produtos definidos como "Brindes"            OPERACIONAL                        NaN
PCREGRACONTABIL                EXCLUI_OPER_ER    VARCHAR2(1)                                                                           23 - Desconsiderar movimentação "ER"            OPERACIONAL                        NaN
PCREGRACONTABIL               DESCLANCESTORNO    VARCHAR2(1)                                 Desconsiderar os lançamentos provenientes de estorno ao buscar os recebimentos            OPERACIONAL                        NaN
PCREGRACONTABIL              DESC_DEP_ATI_IMO    VARCHAR2(1)                                                             06 - Não incluir departamento do Ativo Imobilizado            OPERACIONAL                        NaN
PCREGRACONTABIL              DESC_DEP_MAT_CON    VARCHAR2(1)                                                           07 - Não Incluir departamento de Material de Consumo            OPERACIONAL                        NaN
PCREGRACONTABIL                 VALOR_DEST_NF    VARCHAR2(1)                                                            05 - Apresentar os valores destacado na nota fiscal            OPERACIONAL                        NaN
PCREGRACONTABIL              DESC_NF_DENEGADA    VARCHAR2(1)                                                                                18 - Desconsidera NF-e denegada            OPERACIONAL                        NaN
PCREGRACONTABIL               NF_RATEIO_CONTA    VARCHAR2(1)                                                                      Notas fiscais somente com rateio de conta            OPERACIONAL                        NaN
PCREGRACONTABIL                       FILTROS VARCHAR2(4000)                                                                         Indica os filtros para o SQL da regra.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*