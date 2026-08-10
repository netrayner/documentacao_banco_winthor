# 📊 Tabela: PCELEMENTOFORMULATINTA

### Estrutura de Colunas e Restrições

                Tabela                Coluna  Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCELEMENTOFORMULATINTA            CODMAQUINA   NUMBER(4,0)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA        CHAVEPRINCIPAL  VARCHAR2(40)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA            CODFORMULA  VARCHAR2(25)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA          CODPRODTINTA  VARCHAR2(40)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA                 ORDEM   NUMBER(8,0)                                                                                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA             QTD_GRAMA  NUMBER(12,6)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA               CODBASE  VARCHAR2(40)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA                  QTD1   NUMBER(4,0)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA                  QTD2   NUMBER(4,0)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA                  QTD3   NUMBER(4,0)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA                  QTD4   NUMBER(4,0)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA           QTDETINTAML  NUMBER(18,6)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA              SITUACAO   VARCHAR2(1)                                                                   situação da formula de tinta    CHAVE PRIMÁRIA (PK)                        NaN
PCELEMENTOFORMULATINTA TIPOEMBALAGEMORIGINAL   VARCHAR2(2)                                                  tipo de embalagem\ttipo de embalagem da tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA    QTDETINTAML_QUARTO  NUMBER(18,6)       qtde de tinta em ML para um quarto de tinta\tqtde de tinta em ML para um quarto de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA     QTDETINTAML_GALAO  NUMBER(18,6)         qtde de tinta em ML para um galao de tinta\tqtde de tinta em ML para um galao de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA      QTDETINTAML_LATA  NUMBER(18,6)         qtde de tinta em ML para uma lata de tinta\tqtde de tinta em ML para uma lata de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA           QTD1_QUARTO   NUMBER(4,0) qtde de tinta em Pulso para um quarto de tinta\tqtde de tinta em Pulso para um quarto de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA           QTD2_QUARTO   NUMBER(4,0) qtde de tinta em Pulso para um quarto de tinta\tqtde de tinta em Pulso para um quarto de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA           QTD3_QUARTO   NUMBER(4,0) qtde de tinta em Pulso para um quarto de tinta\tqtde de tinta em Pulso para um quarto de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA           QTD4_QUARTO   NUMBER(4,0) qtde de tinta em Pulso para um quarto de tinta\tqtde de tinta em Pulso para um quarto de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA            QTD1_GALAO   NUMBER(4,0)   qtde de tinta em Pulso para um galao de tinta\tqtde de tinta em Pulso para um galao de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA            QTD2_GALAO   NUMBER(4,0)   qtde de tinta em Pulso para um galao de tinta\tqtde de tinta em Pulso para um galao de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA            QTD3_GALAO   NUMBER(4,0)   qtde de tinta em Pulso para um galao de tinta\tqtde de tinta em Pulso para um galao de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA            QTD4_GALAO   NUMBER(4,0)   qtde de tinta em Pulso para um galao de tinta\tqtde de tinta em Pulso para um galao de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA             QTD1_LATA   NUMBER(4,0)   qtde de tinta em Pulso para uma lata de tinta\tqtde de tinta em Pulso para uma lata de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA             QTD2_LATA   NUMBER(4,0)   qtde de tinta em Pulso para uma lata de tinta\tqtde de tinta em Pulso para uma lata de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA             QTD3_LATA   NUMBER(4,0)   qtde de tinta em Pulso para uma lata de tinta\tqtde de tinta em Pulso para uma lata de tinta            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA             QTD4_LATA   NUMBER(4,0)                                                                                            NaN            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA    INFOTINTAML_QUARTO VARCHAR2(150)                                                                  INFORMAÇÃO  CÁLCULO ML QUARTO            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA     INFOTINTAML_GALAO VARCHAR2(150)                                                                   INFORMAÇÃO  CÁLCULO ML GALÃO            OPERACIONAL                        NaN
PCELEMENTOFORMULATINTA      INFOTINTAML_LATA VARCHAR2(150)                                                                    INFORMAÇÃO  CÁLCULO ML LATA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*