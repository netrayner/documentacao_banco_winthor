# 📊 Tabela: PCLOGDESCQUANT

### Estrutura de Colunas e Restrições

        Tabela                 Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGDESCQUANT                CODPROD  NUMBER(6,0)                                                                             Código do Produto.            OPERACIONAL                        NaN
PCLOGDESCQUANT        INICIOINTERVALO NUMBER(10,4)                                                  Quantidade inicial do item que terá desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT           FIMINTERVALO NUMBER(10,4)                                                    Quantidade final do item que terá desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT               PERCDESC  NUMBER(6,2)                                                                        Percentual de desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT              NUMREGIAO  NUMBER(4,0)                                                   Código da Região que prevalecerá o desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT               DTINICIO         DATE                                    Data Início do período de vigência da política de desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT                  DTFIM         DATE                                       Data Fim do período de vigência da política de desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT               CODPRACA  NUMBER(4,0)                                                    Código da Praça que prevalecerá o desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT            PERCDESCVRJ  NUMBER(6,2)                                                                 Percentual de desconto Varejo.            OPERACIONAL                        NaN
PCLOGDESCQUANT             PERCDESCVP NUMBER(10,4)                                                          Percentual de desconto Venda a Prazo.            OPERACIONAL                        NaN
PCLOGDESCQUANT          PERCDESCFINVV NUMBER(10,4)                                               Percentual de desconto financeiro venda a vista.            OPERACIONAL                        NaN
PCLOGDESCQUANT          PERCDESCFINVP NUMBER(10,4)                                               Percentual de desconto financeiro venda a Prazo.            OPERACIONAL                        NaN
PCLOGDESCQUANT           TIPODESCONTO  VARCHAR2(1)                                                                              Tipo do desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT             PERDESCMAX NUMBER(10,2)                                                                 Percentual máximo de desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT            CODPLPAGMAX  NUMBER(4,0)                                   Indica o Plano de Pagamento máximo para desconto por volume.            OPERACIONAL                        NaN
PCLOGDESCQUANT    CREDITASOBREPTABELA  VARCHAR2(1) Indica se Credita RCA na venda com preço maior que o preço com desconto por volume automático.            OPERACIONAL                        NaN
PCLOGDESCQUANT                   DATA         DATE                                            Data de Exclusão do registro da tabela PCDESCQUANT.            OPERACIONAL                        NaN
PCLOGDESCQUANT            CODDESCONTO  NUMBER(8,0)                                                                   Indica o código do desconto.            OPERACIONAL                        NaN
PCLOGDESCQUANT CONSIDERACALCGIROMEDIC  VARCHAR2(1)                                           Considera politica no calculo do giro (medicamentos)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*