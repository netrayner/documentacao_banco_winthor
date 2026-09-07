# 📊 Tabela: PCWINTHOR_MYFROTA_PROC

### Estrutura de Colunas e Restrições

                Tabela       Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCWINTHOR_MYFROTA_PROC DATAINCLFILA TIMESTAMP(6) Data de inclusão do registro.            OPERACIONAL                        NaN
PCWINTHOR_MYFROTA_PROC        CHAVE          RAW Chave única desta requisição.            OPERACIONAL                        NaN
PCWINTHOR_MYFROTA_PROC     OPERACAO VARCHAR2(50)       Operação da requisição.            OPERACIONAL                        NaN
PCWINTHOR_MYFROTA_PROC        DADOS         CLOB          Dados da requisição.            OPERACIONAL                        NaN
PCWINTHOR_MYFROTA_PROC    DATAENVIO TIMESTAMP(6)  Data de envio da requisição.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*