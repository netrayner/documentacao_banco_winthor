# 📊 Tabela: PCCONFOPERACAOWMS_ITEM

### Estrutura de Colunas e Restrições

                Tabela           Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFOPERACAOWMS_ITEM      CODOPERACAO   NUMBER(4,0)              Código da operação    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFOPERACAOWMS_ITEM TIPOCONFIGURACAO VARCHAR2(100)    Tipo de configuração do ítem    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFOPERACAOWMS_ITEM        SEQUENCIA   NUMBER(4,0)           Sequencia dos valores    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFOPERACAOWMS_ITEM        DESCRICAO VARCHAR2(100)               Descrição do ítem            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM            VALOR VARCHAR2(100)         Valor definido pro ítem            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM        TIPOCAMPO   VARCHAR2(1)           Tipo do campo do ítem    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFOPERACAOWMS_ITEM       DTCADASTRO          DATE                Data do cadastro            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM      DTALTERACAO          DATE               Data da alteração            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM       DTEXCLUSAO          DATE                Data da exclusão            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM    CODUSUARIOCAD   NUMBER(8,0) Código do usuário que cadastrou            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM    CODUSUARIOALT   NUMBER(8,0)   Código do usuário que alterou            OPERACIONAL                        NaN
PCCONFOPERACAOWMS_ITEM    CODUSUARIOEXC   NUMBER(8,0)   Código do usuário que excluiu            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*