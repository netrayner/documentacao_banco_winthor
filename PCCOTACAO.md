# 📊 Tabela: PCCOTACAO

### Estrutura de Colunas e Restrições

   Tabela              Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAO          NUMCOTACAO  NUMBER(8,0)                             Indica o número cotação.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAO       DTINIVIGENCIA         DATE    Indica a data de início para vigência da cotação.            OPERACIONAL                        NaN
PCCOTACAO       DTFIMVIGENCIA         DATE        Indica a data final para vigência da cotação.            OPERACIONAL                        NaN
PCCOTACAO          DTCADASTRO         DATE                              Indica a data cadastro.            OPERACIONAL                        NaN
PCCOTACAO         CODFUNCLANC  NUMBER(8,0)                  Indica o código usuário lançamento.            OPERACIONAL                        NaN
PCCOTACAO           CODROTINA  NUMBER(8,0)                           Indica o código da rotina.            OPERACIONAL                        NaN
PCCOTACAO              NUMPED NUMBER(10,0)                    Indica o pedido de compra gerado.            OPERACIONAL                        NaN
PCCOTACAO TIPOEMBALAGEMPEDIDO  VARCHAR2(1)    Tipo de embalagem dos produtos(Master ou Vendas).            OPERACIONAL                        NaN
PCCOTACAO   UTLPRAZOMEDFORNEC  VARCHAR2(1) Utiliza prazo de pagamento como critico de desempate            OPERACIONAL                        NaN
PCCOTACAO        TIPODESCARGA  VARCHAR2(1)                            Tipo de pedido de compra.            OPERACIONAL                        NaN
PCCOTACAO         TIPOBONIFIC  VARCHAR2(2)                                                  NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*