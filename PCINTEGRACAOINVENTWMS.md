# 📊 Tabela: PCINTEGRACAOINVENTWMS

### Estrutura de Colunas e Restrições

               Tabela            Coluna  Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRACAOINVENTWMS     IDENTIFICADOR VARCHAR2(265)                                   Identificador            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS         NUMINVENT   NUMBER(8,0)                       Numero inventario Winthor            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS           CODPROD   NUMBER(6,0)                               Código de produto            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS           NUMLOTE  VARCHAR2(20)                                  Numero do lote            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS             QTWMS  NUMBER(22,8)              Quantidade total do produto no wms            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS             DTVAL          DATE                                Data de validade            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS         CODFILIAL   VARCHAR2(2)                                Código da Filial            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS       QTAVARIAWMS  NUMBER(20,6)                      Quantidade avariada no wms            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS    QTBLOQUEADAWMS  NUMBER(20,6)                     Quantidade bloqueada no wms            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS      DTINTEGRACAO          DATE                              Data de integração            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS     DTATUALIZACAO          DATE               Data de atualização do inventario            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS     ATUALIZARITEM   VARCHAR2(1)     Informa se o item foi atualizado no Winthor            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS STATUSATUALIZACAO  VARCHAR2(60)                   Status da atualização do item            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS             CUSTO  NUMBER(18,6)                 Custo do Produto na atualização            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS         QTWINTHOR  NUMBER(22,8)            Quantidade no Winthor na atualização            OPERACIONAL                        NaN
PCINTEGRACAOINVENTWMS     QTDISPWINTHOR  NUMBER(22,8) Quantidade disponível no winthor na atualização            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*