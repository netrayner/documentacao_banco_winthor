# 📊 Tabela: PCPRODUT_PROGRAMADA

### Estrutura de Colunas e Restrições

             Tabela          Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUT_PROGRAMADA              ID  NUMBER(6,0)                                                         \tIdentificador de registro da tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUT_PROGRAMADA  DATAPROGRAMADA         DATE               Data programada para a configuração da tributação entrar em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA        APLICADA  VARCHAR2(1) Se a tributação configurada para o produto foi aplicado na data programada (S = SIM; N = NÃO).            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA   DATAAPLICACAO         DATE                                Data e hora da aplicação da configuração tributária no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA         CODPROD  NUMBER(6,0)                   Código do produto que a configuração tributária programada entrará em vigor.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA             NBM VARCHAR2(15)                                                 Código NCM que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA          EXTIPI  VARCHAR2(3)                                            Extensão do IPI que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA        CODNCMEX VARCHAR2(20)                                    Código NCM com extensão que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA    PERCIPIVENDA NUMBER(10,2)                                 Percentual do IPI de Venda que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA VLPAUTAIPIVENDA NUMBER(10,2)                             Valor da Pauta do IPI de Venda que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA VLIPIPORKGVENDA NUMBER(10,2)                       Valor do IPI por Quilo (KG) de Venda que entrará em vigência no produto.            OPERACIONAL                        NaN
PCPRODUT_PROGRAMADA  VLIPIPAUTATV10 NUMBER(10,2)                        Valor de Pauta do IPI na Venda TV10 que entrará em vigência no produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*