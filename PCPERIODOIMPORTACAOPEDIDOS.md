# 📊 Tabela: PCPERIODOIMPORTACAOPEDIDOS

### Estrutura de Colunas e Restrições

                    Tabela             Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERIODOIMPORTACAOPEDIDOS          CODFILIAL  VARCHAR2(2)                                                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCPERIODOIMPORTACAOPEDIDOS            DOMINGO  VARCHAR2(1) Flag que verifica se domingo pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS DOMINGOHORAINICIAL         DATE                Hora inicial que domingo pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS   DOMINGOHORAFINAL         DATE                  Hora final que domingo pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS            SEGUNDA  VARCHAR2(1) Flag que verifica se segunda pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS SEGUNDAHORAINICIAL         DATE                Hora inicial que segunda pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS   SEGUNDAHORAFINAL         DATE                  Hora final que segunda pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS              TERCA  VARCHAR2(1)   Flag que verifica se terça pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS   TERCAHORAINICIAL         DATE                  Hora inicial que terça pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS     TERCAHORAFINAL         DATE                    Hora final que terça pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS             QUARTA  VARCHAR2(1)  Flag que verifica se quarta pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS  QUARTAHORAINICIAL         DATE                 Hora inicial que quarta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS    QUARTAHORAFINAL         DATE                   Hora final que quarta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS             QUINTA  VARCHAR2(1)  Flag que verifica se quinta pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS  QUINTAHORAINICIAL         DATE                 Hora inicial que quinta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS    QUINTAHORAFINAL         DATE                   Hora final que quinta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS              SEXTA  VARCHAR2(1)   Flag que verifica se sexta pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS   SEXTAHORAINICIAL         DATE                  Hora inicial que sexta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS     SEXTAHORAFINAL         DATE                    Hora final que sexta pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS             SABADO  VARCHAR2(1)  Flag que verifica se sabado pode receber importação de pedidos            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS  SABADOHORAINICIAL         DATE                 Hora inicial que sabado pode receber importação            OPERACIONAL                        NaN
PCPERIODOIMPORTACAOPEDIDOS    SABADOHORAFINAL         DATE                   Hora final que sábado pode receber importação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*