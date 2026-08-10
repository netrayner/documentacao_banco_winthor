# 📊 Tabela: PCPRODUTIVIDADEPAGA

### Estrutura de Colunas e Restrições

             Tabela               Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTIVIDADEPAGA CODPRODUTIVIDADEPAGA  NUMBER(6,0)                         Cód. Da produtividade paga.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTIVIDADEPAGA                  MES  VARCHAR2(2)                 Referencia do mês de produtividade.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA                  ANO  VARCHAR2(4)                 Referencia do ano de produtividade.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA    TIPOPRODUTIVIDADE  VARCHAR2(1)                Referencia do itpo de produtividade.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA           CODFUNCSEP  NUMBER(8,0)                                 Cód. Do fornecedor.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA          METAINICIAL NUMBER(20,6)                Valor minimo da meta a ser cumprida.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA            METAFINAL NUMBER(20,6) O maior valor da meta que se espera a ser cumprida.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA           METAAPAGAR NUMBER(20,6)                     Valor a pagar da meta cumprida.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA        METAREALIZADA NUMBER(20,6)                      Meta realizada pelo separador.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA           VLORIGINAL NUMBER(20,6)                  Valor a ser pago para o separador.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA             VLAPAGAR NUMBER(20,6)             Valor real a ser paga para o separador.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA               RECNUM  NUMBER(8,0) Numero que faz referencia ao contas a pagar gerado.            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA         CODMETAVALOR  NUMBER(6,0)                 Código relacionado à meta escolhida            OPERACIONAL                        NaN
PCPRODUTIVIDADEPAGA            CODFILIAL  VARCHAR2(2)                                    Código da filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*