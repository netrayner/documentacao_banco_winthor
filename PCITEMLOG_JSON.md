# 📊 Tabela: PCITEMLOG_JSON

### Estrutura de Colunas e Restrições

        Tabela   Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITEMLOG_JSON   CODIGO NUMBER(18,0)          SEQUENCIAL DE REGISTRO DE GRAVACAO    CHAVE PRIMÁRIA (PK)                        NaN
PCITEMLOG_JSON     DATA         DATE                            DATA DE INCLUSAO            OPERACIONAL                        NaN
PCITEMLOG_JSON  CODPROD  NUMBER(6,0)                           CODIGO DO PRODUTO            OPERACIONAL                        NaN
PCITEMLOG_JSON   NUMSEQ  NUMBER(6,0) NUMERO DE SEQUENCIA DIGITACAO DO MESMO ITEM            OPERACIONAL                        NaN
PCITEMLOG_JSON   NUMPED  NUMBER(8,0)                            NUMERO DO PEDIDO            OPERACIONAL                        NaN
PCITEMLOG_JSON LOG_JSON         CLOB     CAMPO PARA GRAVAR O ARQUIVO JSON DE LOG            OPERACIONAL                        NaN
PCITEMLOG_JSON  MAQUINA VARCHAR2(80)     NOME DA MAQUINA QUE REALIZOU O PROCESSO            OPERACIONAL                        NaN
PCITEMLOG_JSON   ROTINA VARCHAR2(80)              ROTINA QUE REALIZOU A OPERACAO            OPERACIONAL                        NaN
PCITEMLOG_JSON  USUARIO VARCHAR2(80)              USUARIO QUE RELIZOU A OPERACAO            OPERACIONAL                        NaN
PCITEMLOG_JSON SITUACAO VARCHAR2(20)                  TIPO DA OPERACAO REALIZADA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*