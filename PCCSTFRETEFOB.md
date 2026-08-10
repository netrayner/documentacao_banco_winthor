# 📊 Tabela: PCCSTFRETEFOB

### Estrutura de Colunas e Restrições

       Tabela                       Coluna Tipo/Tamanho                                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCSTFRETEFOB                         TIPO  NUMBER(1,0)                                         1 - ICMS , 2 - PISCOFINS            OPERACIONAL                        NaN
PCCSTFRETEFOB                    CODFILIAL  VARCHAR2(2)                                                 Código da Filial            OPERACIONAL                        NaN
PCCSTFRETEFOB                    CODFORNEC  NUMBER(6,0)                                             Código do Fornecedor            OPERACIONAL                        NaN
PCCSTFRETEFOB        CODCSTPISCOFINSTRANSP  NUMBER(3,0)                             Codigo CST PIS/COFINS Transportadora            OPERACIONAL                        NaN
PCCSTFRETEFOB       CODCSTPISCOFINSPRODUTO  NUMBER(3,0)                      Codigo CST PIS/COFINS Tributação de entrada            OPERACIONAL                        NaN
PCCSTFRETEFOB             CODCSTICMSTRANSP  VARCHAR2(3)                                   Codigo CST ICMS Transportadora            OPERACIONAL                        NaN
PCCSTFRETEFOB            CODCSTICMSPRODUTO  VARCHAR2(3)                            Codigo CST ICMS Tributação de entrada            OPERACIONAL                        NaN
PCCSTFRETEFOB                       PERPIS NUMBER(12,4)                                                Percentual de PIS            OPERACIONAL                        NaN
PCCSTFRETEFOB                    PERCOFINS NUMBER(12,4)                                             Percentual de COFINS            OPERACIONAL                        NaN
PCCSTFRETEFOB              GERABASESEMALIQ  VARCHAR2(1)                               Gera Base de PIS/COFINS s/Alíquota            OPERACIONAL                        NaN
PCCSTFRETEFOB                     PERCICMS NUMBER(12,4)                                               Percentual de ICMS            OPERACIONAL                        NaN
PCCSTFRETEFOB             PERCREDICMSCUSTO NUMBER(12,4)                                 Percentual de ICMS p/ Calc.Custo            OPERACIONAL                        NaN
PCCSTFRETEFOB                         CFOP NUMBER(10,0)                                    CFOP do Conhecimento de Frete            OPERACIONAL                        NaN
PCCSTFRETEFOB      CONSPEDAGIOICMSFRETEFOB  VARCHAR2(1)                             Cons. Pedágio na Base ICMS frete FOB            OPERACIONAL                        NaN
PCCSTFRETEFOB CONSPEDAGIOPISCOFINSFRETEFOB  VARCHAR2(1)                       Cons. Pedágio na Base PIS/COFINS frete FOB            OPERACIONAL                        NaN
PCCSTFRETEFOB                  PERCICMSRED NUMBER(18,6)                                    Percentual de Redução de ICMS            OPERACIONAL                        NaN
PCCSTFRETEFOB                        PAUTA NUMBER(18,6)                                           Valor de pauta do ICMS            OPERACIONAL                        NaN
PCCSTFRETEFOB    PERCREDBASEPISCOFINSFRETE NUMBER(12,4)    Percentual de redução da base para o calculo pis/cofins Frete            OPERACIONAL                        NaN
PCCSTFRETEFOB          CODEXCECAOPISCOFINS  NUMBER(6,0) Código de exceção de PIS/COFINS de tributação por transportadora            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*