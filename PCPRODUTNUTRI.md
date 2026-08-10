# 📊 Tabela: PCPRODUTNUTRI

### Estrutura de Colunas e Restrições

       Tabela                    Coluna Tipo/Tamanho                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTNUTRI               CODAUXILIAR NUMBER(16,0)                                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTNUTRI                    PORCAO VARCHAR2(35)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI             VALORCALORICO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI           VDVALORCALORICO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI              CARBOIDRATOS  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI            VDCARBOIDRATOS  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                 PROTEINAS  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI               VDPROTEINAS  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI              GORDURATOTAL  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI            VDGORDURATOTAL  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI           GORDURASATURADA  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI         VDGORDURASATURADA  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                COLESTEROL  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI              VDCOLESTEROL  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI            FIBRAALIMENTAR  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI          VDFIBRAALIMENTAR  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                    CALCIO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                  VDCALCIO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                     FERRO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                   VDFERRO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                     SODIO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI                   VDSODIO  NUMBER(8,3)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI             UNIDADEPORCAO  VARCHAR2(2)                                                     NaN            OPERACIONAL                        NaN
PCPRODUTNUTRI              GORDURATRANS  NUMBER(8,3)             Indica o valor nutricional da gordura tans.            OPERACIONAL                        NaN
PCPRODUTNUTRI            VDGORDURATRANS  NUMBER(8,3)     Indica o valor para consumo diario de gordura trans            OPERACIONAL                        NaN
PCPRODUTNUTRI                    CODIGO  VARCHAR2(6)                        Código da informação nutricional            OPERACIONAL                        NaN
PCPRODUTNUTRI           VALORENERGETICO  NUMBER(8,3)                                 Valor energético (Kcal)            OPERACIONAL                        NaN
PCPRODUTNUTRI               ACUCARESTOT  NUMBER(8,3)                                     Açúcares totais (g)            OPERACIONAL                        NaN
PCPRODUTNUTRI              ACUCARESADIC  NUMBER(8,3)                                 Açúcares adicionados(g)            OPERACIONAL                        NaN
PCPRODUTNUTRI             MEDIDACASEIRA  NUMBER(8,3)                                          Medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRI         VDVALORENERGETICO  NUMBER(8,3)     Indica o valor para consumo diário Valor energético            OPERACIONAL                        NaN
PCPRODUTNUTRI             VDACUCARESTOT  NUMBER(8,3)      Indica o valor para consumo diario Açúcares totais            OPERACIONAL                        NaN
PCPRODUTNUTRI            VDACUCARESADIC  NUMBER(8,3) Indica o valor para consumo diario Açúcares adicionados            OPERACIONAL                        NaN
PCPRODUTNUTRI           VDMEDIDACASEIRA  NUMBER(8,3)       Indica o valor para consumo diario Medida caseira            OPERACIONAL                        NaN
PCPRODUTNUTRI PARTEDECIMALMEDIDACASEIRA  NUMBER(2,0)   \tReferente a Parte Decimal da Medida Caseira do MGV7            OPERACIONAL                        NaN
PCPRODUTNUTRI    MEDIDACASEIRAUTILIZADA  NUMBER(3,0)             Referente a Medida Caseira Utilizada MGV7\t            OPERACIONAL                        NaN
PCPRODUTNUTRI       VALORENERGETICO100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI          CARBOIDRATOS100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI           ACUCARESTOT100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI          ACUCARESADIC100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI             PROTEINAS100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI          GORDURATOTAL100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI       GORDURASATURADA100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI          GORDURATRANS100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI        FIBRAALIMENTAR100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI                 SODIO100G NUMBER(11,3)            Quantidade referente a uma embalagem de 100g            OPERACIONAL                        NaN
PCPRODUTNUTRI                 PORCAOEMB  NUMBER(8,3) Referente a porção por embalagem na integração com MGV7            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*