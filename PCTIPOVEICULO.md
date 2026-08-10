# 📊 Tabela: PCTIPOVEICULO

### Estrutura de Colunas e Restrições

       Tabela                    Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOVEICULO            CODTIPOVEICULO  NUMBER(3,0)               Código do tipo do veículo    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOVEICULO            DSCTIPOVEICULO VARCHAR2(60)            Descrição do tipo do veículo            OPERACIONAL                        NaN
PCTIPOVEICULO          CODPERFILVEICULO  NUMBER(3,0)             Código do perfil do veículo CHAVE ESTRANGEIRA (FK)            PCPERFILVEICULO
PCTIPOVEICULO                TIPODIARIA  VARCHAR2(1)                          Tipo de diária            OPERACIONAL                        NaN
PCTIPOVEICULO                  VLDIARIA NUMBER(12,4)                         Valor da diária            OPERACIONAL                        NaN
PCTIPOVEICULO  TIPOTARIFAKGTRANSPORTADO  VARCHAR2(1)       Tipo deTarifa por Kg transportado            OPERACIONAL                        NaN
PCTIPOVEICULO    VLTARIFAKGTRANSPORTADO NUMBER(12,4)     Valor da Tarifa por Kg transportado            OPERACIONAL                        NaN
PCTIPOVEICULO TIPOTARIFAVOLTRANSPORTADO  VARCHAR2(1)  Tipo de Tarifa por Volume transportado            OPERACIONAL                        NaN
PCTIPOVEICULO   VLTARIFAVOLTRANSPORTADO NUMBER(12,4) Valor da Tarifa por Volume transportado            OPERACIONAL                        NaN
PCTIPOVEICULO      TIPOTARIFAQTDENTREGA  VARCHAR2(1)       Tipo de Tarifa por Qtd de Entrega            OPERACIONAL                        NaN
PCTIPOVEICULO        VLTARIFAQTDENTREGA NUMBER(12,4)      Valor de Tarifa por Qtd de Entrega            OPERACIONAL                        NaN
PCTIPOVEICULO        PERIODOINIVIGENCIA         DATE             Periódo inicial de Vigência            OPERACIONAL                        NaN
PCTIPOVEICULO        PERIODOFIMVIGENCIA         DATE              Periódo Final  de Vigência            OPERACIONAL                        NaN
PCTIPOVEICULO       COMISSAOINCIDESOBRE  VARCHAR2(2)                   Comissão incide sobre            OPERACIONAL                        NaN
PCTIPOVEICULO      PONDERACAOTARIFAPESO  NUMBER(7,4)       Ponderação de tarifa sobre o peso            OPERACIONAL                        NaN
PCTIPOVEICULO    PONDERACAOTARIFAVOLUME  NUMBER(7,4)     Ponderação de tarifa sobre o volume            OPERACIONAL                        NaN
PCTIPOVEICULO   PONDERACAOTARIFAENTREGA  NUMBER(7,4)    Ponderação de tarifa sobre a entrega            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*