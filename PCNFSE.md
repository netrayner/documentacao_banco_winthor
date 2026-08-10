# 📊 Tabela: PCNFSE

### Estrutura de Colunas e Restrições

Tabela              Coluna   Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFSE           CODFILIAL    VARCHAR2(2)                                       Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCNFSE             TIPOMOV    VARCHAR2(1)                                   Tipo da movimentação    CHAVE PRIMÁRIA (PK)                        NaN
PCNFSE        NUMTRANSACAO   NUMBER(10,0)                                    Número da transação    CHAVE PRIMÁRIA (PK)                        NaN
PCNFSE   DATA_HORA_EMISSAO   TIMESTAMP(0)                          Data e hora da emissão da DPS            OPERACIONAL                        NaN
PCNFSE    DATA_COMPETENCIA           DATE                                    Data da competência            OPERACIONAL                        NaN
PCNFSE     COD_MUN_EMISSOR    NUMBER(7,0)                       Código IBGE do município emissor            OPERACIONAL                        NaN
PCNFSE    NOME_MUN_EMISSOR  VARCHAR2(100)                              Nome do município emissor            OPERACIONAL                        NaN
PCNFSE        COD_TRIB_NAC    VARCHAR2(6)                         Código de tributação nacionanl            OPERACIONAL                        NaN
PCNFSE       DESC_TRIB_NAC  VARCHAR2(600)                       Descrição da tributação nacional            OPERACIONAL                        NaN
PCNFSE        COD_TRIB_MUN   VARCHAR2(20)                         Código da tributação municipal            OPERACIONAL                        NaN
PCNFSE       DESC_TRIB_MUN  VARCHAR2(600)                      Descrição da tributação municipal            OPERACIONAL                        NaN
PCNFSE            DESC_NBS  VARCHAR2(600) Descrição da NBS (Nomenclatura Brasileira de Serviços)            OPERACIONAL                        NaN
PCNFSE        DESC_SERVICO VARCHAR2(1000)                          Descrição do serviço prestado            OPERACIONAL                        NaN
PCNFSE            V_BC_ISS   NUMBER(15,2)                               Base de cálculo do ISSQN            OPERACIONAL                        NaN
PCNFSE            ALIQ_ISS   NUMBER(15,2)                               Alíquota do ISS aplicada            OPERACIONAL                        NaN
PCNFSE        V_ISS_RETIDO   NUMBER(15,2)                                    Valor do ISS retido            OPERACIONAL                        NaN
PCNFSE      V_BC_PISCOFINS   NUMBER(15,2)             Valor da base de cálculo para PIS e COFINS            OPERACIONAL                        NaN
PCNFSE               V_PIS   NUMBER(15,2)                                           Valor do PIS            OPERACIONAL                        NaN
PCNFSE            V_COFINS   NUMBER(15,2)                                        Valor do COFINS            OPERACIONAL                        NaN
PCNFSE              V_IRRF   NUMBER(15,2)                       Valor do imposto de renda retido            OPERACIONAL                        NaN
PCNFSE              V_CSLL   NUMBER(15,2)                                   Valor da CSLL retida            OPERACIONAL                        NaN
PCNFSE            V_IBS_UF   NUMBER(15,2)                       Valor do IBS destinado ao estado            OPERACIONAL                        NaN
PCNFSE           V_IBS_MUN   NUMBER(15,2)                    Valor do IBS destinado ao município            OPERACIONAL                        NaN
PCNFSE               V_CBS   NUMBER(15,2)                                           Valor da CBS            OPERACIONAL                        NaN
PCNFSE         CST_IBS_CBS    VARCHAR2(3)                  Código da situação tributária IBS/CBS            OPERACIONAL                        NaN
PCNFSE           V_SERVICO   NUMBER(15,2)                                 Valor bruto do serviço            OPERACIONAL                        NaN
PCNFSE         V_TOTAL_RET   NUMBER(15,2)                     Valor total das retenções federais            OPERACIONAL                        NaN
PCNFSE           V_LIQUIDO   NUMBER(15,2)                    Valor final a ser pago ao prestador            OPERACIONAL                        NaN
PCNFSE            ALIQ_CBS   NUMBER(15,2)                                        Alíquota do CBS            OPERACIONAL                        NaN
PCNFSE         ALIQ_IBS_UF   NUMBER(15,2)                    Alíquota do IBS destinado ao estado            OPERACIONAL                        NaN
PCNFSE        ALIQ_IBS_MUN   NUMBER(15,2)                 Alíquota do IBS destinado ao município            OPERACIONAL                        NaN
PCNFSE            ALIQ_PIS   NUMBER(15,2)                                        Alíquota do PIS            OPERACIONAL                        NaN
PCNFSE         ALIQ_COFINS   NUMBER(15,2)                                     Alíquota do COFINS            OPERACIONAL                        NaN
PCNFSE          V_TRIB_FED   NUMBER(15,2)                 Valor aproximado dos tributos federais            OPERACIONAL                        NaN
PCNFSE          V_TRIB_EST   NUMBER(15,2)                Valor aproximado dos tributos estaduais            OPERACIONAL                        NaN
PCNFSE          V_TRIB_MUN   NUMBER(15,2)               Valor aproximado dos tributos municipais            OPERACIONAL                        NaN
PCNFSE TIPO_RETENCAO_ISSQN    NUMBER(3,0)                              Tipo de retenção do ISSQN            OPERACIONAL                        NaN
PCNFSE    TRIBUTACAO_ISSQN    NUMBER(3,0)                            Tipo de Tributação do ISSQN            OPERACIONAL                        NaN
PCNFSE          CODMUNIBGE   NUMBER(10,0)                               Código municipal do IBGE            OPERACIONAL                        NaN
PCNFSE        V_BC_IBS_CBS   NUMBER(15,2)                    Valor da base de cálculo do IBS/CBS            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*