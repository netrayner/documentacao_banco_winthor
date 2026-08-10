# 📊 Tabela: PCCOTACAOCIAP

### Estrutura de Colunas e Restrições

       Tabela            Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOCIAP        NUMCOTACAO  NUMBER(8,0)                       Número da Cotação    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOCIAP     DTINIVIGENCIA         DATE                             Data Inicio            OPERACIONAL                        NaN
PCCOTACAOCIAP     DTFIMVIGENCIA         DATE                                Data Fim            OPERACIONAL                        NaN
PCCOTACAOCIAP        DTCADASTRO         DATE                         Data da Cotação            OPERACIONAL                        NaN
PCCOTACAOCIAP       CODFUNCLANC  NUMBER(8,0)           Código do usuário de inclusão            OPERACIONAL                        NaN
PCCOTACAOCIAP         CODROTINA  NUMBER(8,0)                        Código da rotina            OPERACIONAL                        NaN
PCCOTACAOCIAP            NUMPED NUMBER(10,0)    Número do pedido de compra vinculado            OPERACIONAL                        NaN
PCCOTACAOCIAP UTLPRAZOMEDFORNEC  VARCHAR2(1)          Utiliza prazo médio Fornecedor            OPERACIONAL                        NaN
PCCOTACAOCIAP        CODPARCELA  NUMBER(6,0) Código Parcela geração C.Pagar Previsto            OPERACIONAL                        NaN
PCCOTACAOCIAP      TIPODESCARGA  VARCHAR2(1)         Tipo descarga geração do pedido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*