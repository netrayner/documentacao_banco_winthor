# 📊 Tabela: PCTABPR_PROGRAMADA

### Estrutura de Colunas e Restrições

            Tabela                 Coluna Tipo/Tamanho                                                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABPR_PROGRAMADA                     ID  NUMBER(6,0)                                                             Identificador de registro da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCTABPR_PROGRAMADA ID_PCPRODUT_PROGRAMADA  NUMBER(6,0)                                         Identificador de registro da tabela PCPRODUT_PROGRAMADA.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA         DATAPROGRAMADA         DATE                 Data programada para a configuração da tributação entrar em vigência no produto.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA               APLICADA  VARCHAR2(1)   Se a tributação configurada para o produto foi aplicado na data programada (S = SIM; N = NÃO).            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA          DATAAPLICACAO         DATE                                  Data e hora da aplicação da configuração tributária no produto.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA                CODPROD  NUMBER(6,0)                     Código do produto que a configuração tributária programada entrará em vigor.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA              NUMREGIAO  NUMBER(4,0)                             Número da região que entrará em vigência na precificação do produto.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA            CALCULARIPI  VARCHAR2(1)          Se a tributação de IPI será calculada na precificação do produto ao entrar em vigência.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA                  CODST  NUMBER(4,0)               Código da Figura Tributária que entrará em em vigência na precificação do produto.            OPERACIONAL                        NaN
PCTABPR_PROGRAMADA       CODTRIBPISCOFINS  NUMBER(4,0) Código da Figura Tributária do PIS/COFINS que entrará em em vigência na precificação do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*