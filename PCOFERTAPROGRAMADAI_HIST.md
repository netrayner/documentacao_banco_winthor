# 📊 Tabela: PCOFERTAPROGRAMADAI_HIST

### Estrutura de Colunas e Restrições

                  Tabela        Coluna  Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOFERTAPROGRAMADAI_HIST     DATAALTER          DATE           Data de alteração            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST     CODFILIAL   VARCHAR2(2)            Código da Filial            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST     CODOFERTA   NUMBER(6,0)            Código da Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST       CODITEM   NUMBER(6,0)              Código do item            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST   CODAUXILIAR  NUMBER(16,0)             Código auxiliar            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST      VLOFERTA  NUMBER(18,6)                  Vl. Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST  MOTIVOOFERTA  VARCHAR2(60)            Motivo da Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST DTEMISSAOETIQ          DATE Data da emissão da etiqueta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST    QTMAXVENDA  NUMBER(10,3)               Qt. Max Venda            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST CODOFERTAORIG   NUMBER(6,0)  Código da oferta de origem            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST   QTMAXOFERTA  NUMBER(22,8)              Qt. Max Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST QTVENDAOFERTA  NUMBER(22,8)            Qt. Venda Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST  VLOFERTAATAC  NUMBER(18,6)          Vl. Oferta Atacado            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST       CODPROD   NUMBER(6,0)           Código do produto            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST  RECOMPOSICAO   VARCHAR2(1)   Produto para recomposição            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST        MOTIVO VARCHAR2(500)            Motivo da Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST  DATAEXCLUSAO          DATE            Data da Exclusão            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAI_HIST     DTALTERC5  TIMESTAMP(6)              Data alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*