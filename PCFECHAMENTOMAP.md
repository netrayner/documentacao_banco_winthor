# 📊 Tabela: PCFECHAMENTOMAP

### Estrutura de Colunas e Restrições

         Tabela                     Coluna   Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFECHAMENTOMAP              NUMTRANSVENDA   NUMBER(10,0)                       Transação de Venda            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     CODCLI    NUMBER(6,0)                        Código do Cliente            OPERACIONAL                        NaN
PCFECHAMENTOMAP                      PREST    VARCHAR2(2)                        Pretação de Venda            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     DUPLIC   NUMBER(10,0)                           Duplicata / NF            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     NUMCAR    NUMBER(8,0)                   Número do Carregamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP                NUMCHECKOUT    NUMBER(8,0)                       Número do Checkout            OPERACIONAL                        NaN
PCFECHAMENTOMAP            CODFUNCCHECKOUT    NUMBER(8,0)          Código do Funcionário Checktout            OPERACIONAL                        NaN
PCFECHAMENTOMAP                      VALOR   NUMBER(10,2)                           Valor Pretação            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     DTVENC           DATE                       Data de Vencimento            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     CODCOB    VARCHAR2(4)                       Código de Cobrança            OPERACIONAL                        NaN
PCFECHAMENTOMAP                      VPAGO   NUMBER(10,2)                               Valor Pago            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     TXPERM   NUMBER(10,2)                              Valor Juros            OPERACIONAL                        NaN
PCFECHAMENTOMAP                      DTPAG           DATE                        Data de Pagamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP                  DTEMISSAO           DATE                          Data de Emissão            OPERACIONAL                        NaN
PCFECHAMENTOMAP                    PERDESC    NUMBER(6,2)                   Percentual de Desconto            OPERACIONAL                        NaN
PCFECHAMENTOMAP                  CODFILIAL    VARCHAR2(2)                         Código da Filial            OPERACIONAL                        NaN
PCFECHAMENTOMAP                 DTVENCORIG           DATE                    Data de Venc Original            OPERACIONAL                        NaN
PCFECHAMENTOMAP                 CODCOBORIG    VARCHAR2(4)                   Cod. Cobrança Original            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     NSUTEF   VARCHAR2(15)                                  NSU TEF            OPERACIONAL                        NaN
PCFECHAMENTOMAP                   PRESTTEF    NUMBER(2,0)                                Prest TEF            OPERACIONAL                        NaN
PCFECHAMENTOMAP              QTPARCELASPOS    NUMBER(3,0)                  Quantidade Parcelas POS            OPERACIONAL                        NaN
PCFECHAMENTOMAP              OBSERVACAOMAP VARCHAR2(4000)                    Observação Mapeamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP                       DATA           DATE                          Data Mapeamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP        GERAPARCELAMENTOTEF    VARCHAR2(1)                   Gerar Parcelamento TEF            OPERACIONAL                        NaN
PCFECHAMENTOMAP        INFORMADADOSBXCCRED    VARCHAR2(1)                  Informa dados de Cartão            OPERACIONAL                        NaN
PCFECHAMENTOMAP        DESDCARTAOFECHCARGA    VARCHAR2(1)            Desdobra Cartão no Fechamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP USOUPARCELAMENTOAUTOMATICO    VARCHAR2(1)            Usou Desdobramento Automático            OPERACIONAL                        NaN
PCFECHAMENTOMAP     USOUPARCELAMENTOMANUAL    VARCHAR2(1)                Usou Desdobramento Manual            OPERACIONAL                        NaN
PCFECHAMENTOMAP          TITCOMNUMCARCAIXA    VARCHAR2(1)              Exibe Carregamento no Caixa            OPERACIONAL                        NaN
PCFECHAMENTOMAP         PERMITEVENDAECF402    VARCHAR2(1)              Exibe Caixa no Carregamento            OPERACIONAL                        NaN
PCFECHAMENTOMAP                     NUMSEQ   NUMBER(18,0)                        Número Sequencial            OPERACIONAL                        NaN
PCFECHAMENTOMAP             TIPOFECHAMENTO  VARCHAR2(100) Carregamento / Caixa / Carregamento Zero            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*