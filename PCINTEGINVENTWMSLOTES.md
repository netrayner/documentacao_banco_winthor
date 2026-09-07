# 📊 Tabela: PCINTEGINVENTWMSLOTES

### Estrutura de Colunas e Restrições

               Tabela         Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGINVENTWMSLOTES  IDENTIFICADOR VARCHAR2(265)                Identificador            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES      NUMINVENT   NUMBER(8,0)            Numero inventario            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES        CODPROD   NUMBER(6,0)            Código do produto            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES        NUMLOTE  VARCHAR2(20)               Numero do lote            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES          QTWMS  NUMBER(20,8)            Quantidade no wms            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES          DTVAL          DATE             Data de validade            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES      CODFILIAL   VARCHAR2(2)             Código da filial            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES    QTAVARIAWMS  NUMBER(20,6)  Quantidade avariada do lote            OPERACIONAL                        NaN
PCINTEGINVENTWMSLOTES QTBLOQUEADAWMS  NUMBER(20,6) Quantidade bloqueada do lote            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*