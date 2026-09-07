# 📊 Tabela: PCOFERTAPROGRAMADAI

### Estrutura de Colunas e Restrições

             Tabela        Coluna  Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOFERTAPROGRAMADAI     CODFILIAL   VARCHAR2(2)                                                     Código da Filial.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI     CODOFERTA   NUMBER(6,0)                                                     Código da Oferta.    CHAVE PRIMÁRIA (PK)                        NaN
PCOFERTAPROGRAMADAI       CODITEM   NUMBER(6,0)                                                       Código do Item.    CHAVE PRIMÁRIA (PK)                        NaN
PCOFERTAPROGRAMADAI   CODAUXILIAR  NUMBER(16,0)                                                  Código da Embalagem.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI      VLOFERTA  NUMBER(18,6)                                                      Valor da oferta.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI  MOTIVOOFERTA  VARCHAR2(60)                                                      Motivo da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI DTEMISSAOETIQ          DATE                                Data da emissão de etiqueta da oferta.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI    QTMAXVENDA  NUMBER(10,3)            Quantidade máxima do item em oferta para cada cupom fiscal            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI CODOFERTAORIG   NUMBER(6,0)                         Códito da oferta a qual o item obteve o preço            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI   QTMAXOFERTA  NUMBER(22,8)                               Quantidade Máxima do produto em oferta.            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI QTVENDAOFERTA  NUMBER(22,8)                              Quantidade de produto vendidos na oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI  VLOFERTAATAC  NUMBER(18,6)                                                  Valor oferta Atacado            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI       CODPROD   NUMBER(6,0)                                                     Código do rpdouto            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI  RECOMPOSICAO   VARCHAR2(1)                                             Porduto é de recomposição            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI        MOTIVO VARCHAR2(500)                                  Observação do motivo da recomposição            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI  DATAEXCLUSAO          DATE Define a data que o item foi excluído devido a alteração do seu preço            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI     DTALTERC5  TIMESTAMP(6)                                                     Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*