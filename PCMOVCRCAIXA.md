# 📊 Tabela: PCMOVCRCAIXA

### Estrutura de Colunas e Restrições

      Tabela       Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVCRCAIXA     NUMTRANS  NUMBER(8,0) Armazena código do banco o qual caixa foi acertado.            OPERACIONAL                        NaN
PCMOVCRCAIXA     CODCONTA NUMBER(10,0)           Indica o código conta receita ou despesa.            OPERACIONAL                        NaN
PCMOVCRCAIXA       NUMDOC NUMBER(10,0)                       Indica o número do documento.            OPERACIONAL                        NaN
PCMOVCRCAIXA       SEQDOC  VARCHAR2(8)                    Indica o sequência do documento.            OPERACIONAL                        NaN
PCMOVCRCAIXA       CODCOB  VARCHAR2(4)                           Indica o código cobrança.            OPERACIONAL                        NaN
PCMOVCRCAIXA TIPOPARCEIRO  VARCHAR2(2)                          Indica o tipo do parceiro.            OPERACIONAL                        NaN
PCMOVCRCAIXA  CODPARCEIRO  NUMBER(6,0)                        Indica o código do parceiro.            OPERACIONAL                        NaN
PCMOVCRCAIXA       DTVENC         DATE                        Indica o data de vencimento.            OPERACIONAL                        NaN
PCMOVCRCAIXA        VALOR NUMBER(18,6)                           Indica o valor documento.            OPERACIONAL                        NaN
PCMOVCRCAIXA        VPAGO NUMBER(18,6)                                Indica o valor pago.            OPERACIONAL                        NaN
PCMOVCRCAIXA    CODFILIAL  VARCHAR2(2)                          Indica o código da filial.            OPERACIONAL                        NaN
PCMOVCRCAIXA     OPERACAO VARCHAR2(20)                          Indica o tipo de operação.            OPERACIONAL                        NaN
PCMOVCRCAIXA      CODFUNC  NUMBER(6,0) Indica o código funcionário responsável pelo caixa.            OPERACIONAL                        NaN
PCMOVCRCAIXA       TXPERM NUMBER(18,6)                           Indica o valor dos juros.            OPERACIONAL                        NaN
PCMOVCRCAIXA    VALORDESC NUMBER(18,6)                         Indica o valor do desconto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*