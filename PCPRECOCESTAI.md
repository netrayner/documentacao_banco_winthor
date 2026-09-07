# 📊 Tabela: PCPRECOCESTAI

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                                                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRECOCESTAI CODPRECOCESTA NUMBER(10,0)                                                                                                                  Indica o código do preço da cesta.            OPERACIONAL                        NaN
PCPRECOCESTAI   CODPRODACAB  NUMBER(6,0)                                                                                                                 Indica o código do produto acabado.            OPERACIONAL                        NaN
PCPRECOCESTAI     CODPRODMP  NUMBER(6,0)                                                                                                           Indica o código do produto matéria-prima.            OPERACIONAL                        NaN
PCPRECOCESTAI     PRECOFIXO NUMBER(18,6)                                                                                                                                Indica o preço fixo.            OPERACIONAL                        NaN
PCPRECOCESTAI      PERCDESC NUMBER(18,6) Percentual de desconto concedido em uma embalagem da cesta ou kit. Este percentual será aplicado ao preço da embalagem vigente no momento da venda.            OPERACIONAL                        NaN
PCPRECOCESTAI     CODFILIAL  VARCHAR2(2)                                                                                                            Código da Filial vinculada a este preço.            OPERACIONAL                        NaN
PCPRECOCESTAI CODAUXILIARMP NUMBER(20,0)                                                                                      Código auxiliar da embalagem escolhida para esta matéria prima            OPERACIONAL                        NaN
PCPRECOCESTAI       POFERTA NUMBER(22,6)                                                                                                                              Preço de oferta varejo            OPERACIONAL                        NaN
PCPRECOCESTAI   POFERTAATAC NUMBER(22,6)                                                                                                                             Preço de oferta atacado            OPERACIONAL                        NaN
PCPRECOCESTAI     DTALTERC5 TIMESTAMP(6)                                                                                                                                   Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*