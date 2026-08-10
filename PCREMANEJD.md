# 📊 Tabela: PCREMANEJD

### Estrutura de Colunas e Restrições

    Tabela              Coluna  Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREMANEJD         CODREMANEJI  NUMBER(10,0) Código que identifica a combinação: nº pedido, cod. Filial origem, cod. Filial destino e nº remessa remanejamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCREMANEJD          NUMREMESSA  NUMBER(10,0)                                                                                Número da remessa de remanejamento. CHAVE ESTRANGEIRA (FK)                  PCREMANEJ
PCREMANEJD              NUMPED  NUMBER(10,0)                                                                                            Número do pedido TV=10.            OPERACIONAL                        NaN
PCREMANEJD       CODFILIALORIG   VARCHAR2(2)                                                                                              Código filial origem.            OPERACIONAL                        NaN
PCREMANEJD       CODFILIALDEST   VARCHAR2(2)                                                                                             Código filial destino.            OPERACIONAL                        NaN
PCREMANEJD      DTFINALIZAORIG          DATE                                                                                  Data finalização da etapa origem.            OPERACIONAL                        NaN
PCREMANEJD      DTFINALIZADEST          DATE                                                                                 Data finalização da etapa destino.            OPERACIONAL                        NaN
PCREMANEJD    MOTIVODIVERGORIG VARCHAR2(500)                                                                                         Motivo divergência origem.            OPERACIONAL                        NaN
PCREMANEJD    MOTIVODIVERGDEST VARCHAR2(500)                                                                                        Motivo divergência destino.            OPERACIONAL                        NaN
PCREMANEJD CODFUNCFINALIZAORIG   NUMBER(6,0)                                                Código do funcionário responsável pela finalização da etapa origem.            OPERACIONAL                        NaN
PCREMANEJD CODFUNCFINALIZADEST   NUMBER(6,0)                                               Código do funcionário responsável pela finalização da etapa destino.            OPERACIONAL                        NaN
PCREMANEJD    HORAFINALIZAORIG   NUMBER(4,0)                                                                           Hora finalização etapa na filial origem.            OPERACIONAL                        NaN
PCREMANEJD    HORAFINALIZADEST   NUMBER(4,0)                                                                          Hora finalização etapa na filial destino.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*