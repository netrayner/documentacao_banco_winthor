# 📊 Tabela: PCMYFROTA_PROC

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMYFROTA_PROC DATAINCLFILA TIMESTAMP(6)  Data de inclusão na fila.            OPERACIONAL                        NaN
PCMYFROTA_PROC        CHAVE          RAW    Chave de identificação.            OPERACIONAL                        NaN
PCMYFROTA_PROC     OPERACAO VARCHAR2(50)        Operação realizada.            OPERACIONAL                        NaN
PCMYFROTA_PROC        DADOS         CLOB         Valores alterados.            OPERACIONAL                        NaN
PCMYFROTA_PROC    DATAENVIO TIMESTAMP(6) Data de envio dos valores.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*