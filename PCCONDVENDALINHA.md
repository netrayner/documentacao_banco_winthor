# 📊 Tabela: PCCONDVENDALINHA

### Estrutura de Colunas e Restrições

          Tabela                  Coluna Tipo/Tamanho                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONDVENDALINHA        CODCONDICAOVENDA  NUMBER(6,0)                          Código da condição de venda    CHAVE PRIMÁRIA (PK)                        NaN
PCCONDVENDALINHA           CODLINHAPRAZO  NUMBER(6,0)                             Código da linha de prazo    CHAVE PRIMÁRIA (PK)                        NaN
PCCONDVENDALINHA                CODPLPAG  NUMBER(4,0)                         Código do plano de pagamento            OPERACIONAL                        NaN
PCCONDVENDALINHA       PERCDESCBONIFNOTA NUMBER(12,4)          Percentual de desconto de bonificação da NF            OPERACIONAL                        NaN
PCCONDVENDALINHA          PERCDESCOMNOTA NUMBER(12,4)               Percentual de desconto comercial da NF            OPERACIONAL                        NaN
PCCONDVENDALINHA          PERCDESCBOLETO NUMBER(12,4)                     Percentual de desconto do Boleto            OPERACIONAL                        NaN
PCCONDVENDALINHA    TIPOINCIDENCIADESCOM  VARCHAR2(1)           Tipo de incidência da política de desconto            OPERACIONAL                        NaN
PCCONDVENDALINHA             PERCDESCFIN NUMBER(12,4) Percentual de desconto financeiro por linha de prazo            OPERACIONAL                        NaN
PCCONDVENDALINHA TIPOVALIDADESCINDUSTRIA  VARCHAR2(1)           Tipo de Validação do Desconto da Indústria            OPERACIONAL                        NaN
PCCONDVENDALINHA        DESCMAXINDUSTRIA NUMBER(12,4)                         Desconto Máximo da Indústria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*