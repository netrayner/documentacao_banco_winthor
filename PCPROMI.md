# 📊 Tabela: PCPROMI

### Estrutura de Colunas e Restrições

 Tabela            Coluna Tipo/Tamanho                                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROMI            CODIGO  NUMBER(6,0)                                                                                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMI           CODPROD  NUMBER(6,0)                                                                                                                                 NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMI                QT NUMBER(20,6)                                                                                                                 Descricao coluna QT    CHAVE PRIMÁRIA (PK)                        NaN
PCPROMI        VLVENDAMIN NUMBER(12,2)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI        VLVENDAMAX NUMBER(12,2)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI        QTMAXVENDA NUMBER(16,3)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI          QTMAXDIA NUMBER(16,3)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI       CODPROPRINC  NUMBER(6,0)                                                            Código da campanha principal. Permite agrupar varias campanhas a uma só.            OPERACIONAL                        NaN
PCPROMI RESTRICAOVALORMIN NUMBER(18,6)                                                                                                              Restrição valor mínimo            OPERACIONAL                        NaN
PCPROMI    RESTRICAOQTMIN  NUMBER(6,0)                                                                                                                  Quantidade mínima.            OPERACIONAL                        NaN
PCPROMI    RESTRICAOGRUPO  VARCHAR2(1)                                                                                                                 Restrição ao grupo.            OPERACIONAL                        NaN
PCPROMI         PRODOBRIG  VARCHAR2(1)                                                                                                                Produto Obrigatório.            OPERACIONAL                        NaN
PCPROMI    QTLIMITEBRINDE  NUMBER(6,2) Campo para armazenar a quantidade limite para o brinde, com o objetivo de servir como limitador adicional para término de campanhas            OPERACIONAL                        NaN
PCPROMI            SYNCFV  VARCHAR2(1)                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI       CODAUXILIAR NUMBER(20,0)                                                                                                           Código Auxiliar Embalagem            OPERACIONAL                        NaN
PCPROMI        DTMXSALTER         DATE                                                                                                                                 NaN            OPERACIONAL                        NaN
PCPROMI         DTALTERC5 TIMESTAMP(6)                                                            Coluna de identifição de alteração para integracao com PDV Supermercados            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*