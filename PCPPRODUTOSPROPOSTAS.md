# 📊 Tabela: PCPPRODUTOSPROPOSTAS

### Estrutura de Colunas e Restrições

              Tabela                         Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPPRODUTOSPROPOSTAS                      CODEDITAL   NUMBER(9,0)                 Códigoedital.    CHAVE PRIMÁRIA (PK)                        NaN
PCPPRODUTOSPROPOSTAS                        CODPROD   NUMBER(9,0)                Códigoproduto.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                           LOTE  VARCHAR2(10)                         Lote.    CHAVE PRIMÁRIA (PK)                        NaN
PCPPRODUTOSPROPOSTAS                    NUMERO_ITEM   NUMBER(9,0)                 Numerodoitem.    CHAVE PRIMÁRIA (PK)                        NaN
PCPPRODUTOSPROPOSTAS                     TIPO_PRECO       CHAR(1)                    Tipopreço.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS               CUSTO_NO_EMPENHO  NUMBER(18,6)               Custonoempenho.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                      EMPENHADO       CHAR(1)                    Empenhado.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS               GANHOU_LICITACAO       CHAR(1)              Ganhoulicitação.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS             OBSERVACAO_EMPENHO VARCHAR2(100)          Observaçãodeempenho.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS              PERCENTUAL_COFINS  NUMBER(18,6)             Percentualcofins.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS            PERCENTUAL_COMISSAO  NUMBER(18,6)           Percentualcomissão.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS PERCENTUAL_CONTRIBUICAO_SOCIAL  NUMBER(18,6) Percentualcontribuiçãosocial.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                PERCENTUAL_CPMF  NUMBER(18,6)               PercentualCPMF.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS          PERCENTUAL_CUSTO_FIXO  NUMBER(18,6)          Percentualcustofixo.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS     PERCENTUAL_DESCONTO_COMPRA  NUMBER(18,6)     Percentualdescontocompra.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS               PERCENTUAL_FRETE  NUMBER(18,6)              Percentualfrete.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS         PERCENTUAL_FRETE_VENDA  NUMBER(18,6)         Percentualfretevenda.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS         PERCENTUAL_ICMS_COMPRA  NUMBER(18,6)         PercentualICMScompra.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS          PERCENTUAL_ICMS_VENDA  NUMBER(18,6)          PercentualICMSvenda.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                 PERCENTUAL_IPI  NUMBER(18,6)                PercentualIPI.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                  PERCENTUAL_IR  NUMBER(18,6)                 PercentualIR.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS               PERCENTUAL_LUCRO  NUMBER(18,6)            Percentualdelucro.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                 PERCENTUAL_PIS  NUMBER(18,6)                PercentualPIS.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS      PERCENTUAL_REPASSE_COMPRA  NUMBER(18,6)      Percentualrepassecompra.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS            PERCENTUAL_RETENCAO  NUMBER(18,6)           Percentualretenção.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                   PRECO_COMPRA  NUMBER(18,6)                  Preçocompra.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                  PRECO_INICIAL  NUMBER(18,6)                 Preçoinicial.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                   PRECO_MINIMO  NUMBER(18,6)                  Preçominimo.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS                    PRECO_VENDA  NUMBER(18,6)                   Preçovenda.            OPERACIONAL                        NaN
PCPPRODUTOSPROPOSTAS          QTD_ACRESCIMO_EMPENHO  NUMBER(10,0) Quantidadeacrescimodeempenho.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*