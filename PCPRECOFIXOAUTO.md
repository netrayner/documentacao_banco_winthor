# 📊 Tabela: PCPRECOFIXOAUTO

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRECOFIXOAUTO            CODIGO  NUMBER(6,0)                       Código    CHAVE PRIMÁRIA (PK)                        NaN
PCPRECOFIXOAUTO          DTINICIO         DATE                 Data inicial            OPERACIONAL                        NaN
PCPRECOFIXOAUTO             DTFIM         DATE                   Data final            OPERACIONAL                        NaN
PCPRECOFIXOAUTO      TIPOPOLITICA  VARCHAR2(1)                Tipo política            OPERACIONAL                        NaN
PCPRECOFIXOAUTO         CODFILIAL  VARCHAR2(2)                Código Filial            OPERACIONAL                        NaN
PCPRECOFIXOAUTO           CODPROD  NUMBER(6,0)            Código do produto            OPERACIONAL                        NaN
PCPRECOFIXOAUTO        CODTIPOCLI NUMBER(10,0)    Código do tipo de cliente            OPERACIONAL                        NaN
PCPRECOFIXOAUTO            CODCLI  NUMBER(6,0)            Código do Cliente            OPERACIONAL                        NaN
PCPRECOFIXOAUTO         PRECOFIXO NUMBER(18,6)                   Preço Fixo            OPERACIONAL                        NaN
PCPRECOFIXOAUTO      PERCCOMISSAO  NUMBER(6,2)       Percentual de Comissão            OPERACIONAL                        NaN
PCPRECOFIXOAUTO QTINICIOINTERVALO NUMBER(10,0) Quantidade intervalo inicial            OPERACIONAL                        NaN
PCPRECOFIXOAUTO    QTFIMINTERVALO NUMBER(10,0)   Quantidade intervalo final            OPERACIONAL                        NaN
PCPRECOFIXOAUTO          QTOFERTA NUMBER(10,0)         Quantidade da Oferta            OPERACIONAL                        NaN
PCPRECOFIXOAUTO          DTCANCEL         DATE         Data de Cancelamento            OPERACIONAL                        NaN
PCPRECOFIXOAUTO          QTMINIMA NUMBER(10,0)            Quantidade mínima            OPERACIONAL                        NaN
PCPRECOFIXOAUTO          MULTIPLO NUMBER(10,0)                      Mutiplo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*