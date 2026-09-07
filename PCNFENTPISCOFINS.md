# 📊 Tabela: PCNFENTPISCOFINS

### Estrutura de Colunas e Restrições

          Tabela                    Coluna  Tipo/Tamanho                                                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFENTPISCOFINS          CODTRIBPISCOFINS   NUMBER(3,0)                                       Código situação tributária PIS/COFINS    CHAVE PRIMÁRIA (PK)                        NaN
PCNFENTPISCOFINS                 VLBASEPIS  NUMBER(18,6)                                                           Valor da base PIS            OPERACIONAL                        NaN
PCNFENTPISCOFINS              VLBASECOFINS  NUMBER(18,6)                                                        Valor da base COFINS            OPERACIONAL                        NaN
PCNFENTPISCOFINS                    PERPIS  NUMBER(12,4)                                                  Valor do percentual do PIS    CHAVE PRIMÁRIA (PK)                        NaN
PCNFENTPISCOFINS                 PERCOFINS  NUMBER(12,4)                                               Valor do percentual do COFINS    CHAVE PRIMÁRIA (PK)                        NaN
PCNFENTPISCOFINS                  VLCOFINS  NUMBER(18,6)                                                             Valor do Cofins            OPERACIONAL                        NaN
PCNFENTPISCOFINS                     VLPIS  NUMBER(18,6)                                                                Valor do Pis            OPERACIONAL                        NaN
PCNFENTPISCOFINS               NUMTRANSENT  NUMBER(10,0)                                                 Número transação de entrada            OPERACIONAL                        NaN
PCNFENTPISCOFINS                NATCREDITO   VARCHAR2(2) Natureza de Crédito de PIS/COFINS das notas fiscais de serviços adquiridos.            OPERACIONAL                        NaN
PCNFENTPISCOFINS         NUMTRANSPISCOFINS  NUMBER(10,0)                                          Número de transação de PIS/COFINS.    CHAVE PRIMÁRIA (PK)                        NaN
PCNFENTPISCOFINS                   CODCONT  NUMBER(10,0)                                                              Conta contábil            OPERACIONAL                        NaN
PCNFENTPISCOFINS          CODCONTACONTSPED VARCHAR2(255)                         Código da conta contábil que será utilizada no sped            OPERACIONAL                        NaN
PCNFENTPISCOFINS PERCREDBASEPISCOFINSFRETE  NUMBER(12,4)               Percentual de redução da base para o calculo pis/cofins Frete            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*