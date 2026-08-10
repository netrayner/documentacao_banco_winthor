# 📊 Tabela: PCCONTROLEDEENTREGA

### Estrutura de Colunas e Restrições

             Tabela              Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLEDEENTREGA       NUMTRANSVENDA  NUMBER(10,0)                 Indica o numero de transação de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLEDEENTREGA     CODPRACADESTINO   NUMBER(6,0)                    Indica o código destino da entrega.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA            DATAHORA          DATE                       Indica o data e hora de geração.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA              CODCLI   NUMBER(6,0)                            Indica o código do cliente.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA           CODFILIAL   VARCHAR2(2)                             Indica o código da filial.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA        CODMOTORISTA   NUMBER(8,0)                          Indica o código do motorista.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA           DATASAIDA          DATE                         Indica o data e hora de saída.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA         DATARETORNO          DATE                       Indica o data e hora de retorno.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA              NUMDOC  NUMBER(10,0)                          Indica o número do documento.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA            VALORDOC  NUMBER(12,2)                           Indica o valor do documento.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA          VALORFRETE  NUMBER(12,2)                               Indica o valor do frete.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA VALORFRETEADICIONAL  NUMBER(12,2)                     Indica o valor de frete adicional.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA  VALORCOMISSAOFRETE  NUMBER(12,2)          Indica o valor da comissão paga esta entrega.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA                 OBS VARCHAR2(200)                                  Indica a observações.            OPERACIONAL                        NaN
PCCONTROLEDEENTREGA       DTPAGCOMISSAO          DATE Indica quando a comissão foi paga para o profissional.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*