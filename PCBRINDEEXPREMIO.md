# 📊 Tabela: PCBRINDEEXPREMIO

### Estrutura de Colunas e Restrições

          Tabela                Coluna Tipo/Tamanho                                                                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBRINDEEXPREMIO               CODBREX  NUMBER(6,0)                                                                                                         Código da campanha.    CHAVE PRIMÁRIA (PK)                        NaN
PCBRINDEEXPREMIO               CODPROD  NUMBER(6,0)                                                                                              Código do produto em campanha.    CHAVE PRIMÁRIA (PK)                        NaN
PCBRINDEEXPREMIO                    QT NUMBER(18,6)                                                                                          Quantidade do produto em campanha.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO            GRUPOREGRA  NUMBER(6,0)                                                                                                   Código do grupo da regra.    CHAVE PRIMÁRIA (PK)                        NaN
PCBRINDEEXPREMIO          QTMAXBRINDES NUMBER(18,6)                                                                                               Quantidade máxima de brindes.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO         QTBRINDESDISP NUMBER(18,6)                                                                                        Quantidade disponivel para o brinde.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO        ACEITAMULTIPLO  VARCHAR2(1) S/"N", determina se a campanha irá multiplicar os brindes conforme a quantidade de vezes em que o pedido atender as regras.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO         QTMAXMULTIPLO  NUMBER(6,0)                                                                                                   Quantida máxima multiplo.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO SUBSTBRINDEPORSIMILAR  VARCHAR2(1)          "S"/"N", determina se a campanha poderá substituir o brinde por produto similar caso não possua estoque para este.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO       QTMAXBRINDESCLI NUMBER(18,6)                                                                                 Qtde máx. de brindes para cliente por item.            OPERACIONAL                        NaN
PCBRINDEEXPREMIO    QTMAXBRINDESSUPERV NUMBER(18,6)                                                                                 Quantidade máxima de brindes por Supervisor            OPERACIONAL                        NaN
PCBRINDEEXPREMIO       QTMAXBRINDESRCA NUMBER(18,6)                                                                                        Quantidade máxima de brindes por RCA            OPERACIONAL                        NaN
PCBRINDEEXPREMIO          CODFILIALEMB  VARCHAR2(2)                                                                              Código filial da embalagem usada para o brinde            OPERACIONAL                        NaN
PCBRINDEEXPREMIO           CODAUXILIAR NUMBER(20,0)                                                                            Código auxiliar da embalagem usada para o brinde            OPERACIONAL                        NaN
PCBRINDEEXPREMIO            DTMXSALTER         DATE                                                                                                                         NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*