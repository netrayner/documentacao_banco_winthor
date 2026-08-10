# 📊 Tabela: PCTRAFEGOREGISTROS

### Estrutura de Colunas e Restrições

            Tabela     Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTRAFEGOREGISTROS       DATA          DATE             Data de inclusão do registro.            OPERACIONAL                        NaN
PCTRAFEGOREGISTROS     TABELA  VARCHAR2(30)                       Tabela do registro.            OPERACIONAL                        NaN
PCTRAFEGOREGISTROS VALORROWID  VARCHAR2(40)      Identificação do registro na origem.            OPERACIONAL                        NaN
PCTRAFEGOREGISTROS        TAG   VARCHAR2(3)                Identificação da operação.            OPERACIONAL                        NaN
PCTRAFEGOREGISTROS        OBS VARCHAR2(200) Observações sobre a inclusão do registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*