# 📊 Tabela: PCLOGDESCVENDOR

### Estrutura de Colunas e Restrições

         Tabela           Coluna  Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDESCVENDOR           DUPLIC  NUMBER(10,0)                       Numero da nota do título            OPERACIONAL                        NaN
PCLOGDESCVENDOR            PREST   VARCHAR2(2)                            Prestacao do titulo            OPERACIONAL                        NaN
PCLOGDESCVENDOR            VALOR  NUMBER(10,2)                                Valor do titulo            OPERACIONAL                        NaN
PCLOGDESCVENDOR   CONTRATOVENDOR  NUMBER(10,0)          Numero do contrato de desconto/vendor            OPERACIONAL                        NaN
PCLOGDESCVENDOR    DTFECHAVENDOR          DATE                Data de fechamento do documento            OPERACIONAL                        NaN
PCLOGDESCVENDOR       OBSERVACAO VARCHAR2(300)                          Observacao adicionais            OPERACIONAL                        NaN
PCLOGDESCVENDOR       VLTXVENDOR  NUMBER(14,6)                        Valor da taxa de vendor            OPERACIONAL                        NaN
PCLOGDESCVENDOR VLCONTRATOVENDOR  NUMBER(10,2)                    Valor do contrato de vendor            OPERACIONAL                        NaN
PCLOGDESCVENDOR VLCUSTODOCVENDOR  NUMBER(10,2)                    Valor de custo do documento            OPERACIONAL                        NaN
PCLOGDESCVENDOR   CODBANCOVENDOR   NUMBER(4,0)                      Codigo do banco de vendor            OPERACIONAL                        NaN
PCLOGDESCVENDOR         DTCANCEL          DATE              Data de cancelamento do documento            OPERACIONAL                        NaN
PCLOGDESCVENDOR    CODFUNCCANCEL   NUMBER(8,0) Codigo do funcionario que cancelou o documento            OPERACIONAL                        NaN
PCLOGDESCVENDOR   NUMTRANSVENDOR   NUMBER(8,0)               Numero de transacao do documento            OPERACIONAL                        NaN
PCLOGDESCVENDOR    NUMTRANSVENDA  NUMBER(10,0)         Numero de transacao de venda do titulo            OPERACIONAL                        NaN
PCLOGDESCVENDOR        CODFILIAL   VARCHAR2(2)                     Codigo da filial do titulo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*