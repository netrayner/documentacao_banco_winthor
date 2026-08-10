# 📊 Tabela: PCMONITORAMENTO

### Estrutura de Colunas e Restrições

         Tabela      Coluna   Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMONITORAMENTO   SEQUENCIA   NUMBER(12,0)         Sequence da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCMONITORAMENTO      ROTINA  VARCHAR2(200) Codigo da Rotina de origem            OPERACIONAL                        NaN
PCMONITORAMENTO EQUIPAMENTO  VARCHAR2(200)  Nome da Maquina de origem            OPERACIONAL                        NaN
PCMONITORAMENTO     USUARIO  VARCHAR2(100)          Usuário de Origem            OPERACIONAL                        NaN
PCMONITORAMENTO        DATA           DATE           Data do registro            OPERACIONAL                        NaN
PCMONITORAMENTO        HORA   VARCHAR2(10)           Hora do Registro            OPERACIONAL                        NaN
PCMONITORAMENTO       FONTE VARCHAR2(2000)            Fonte de Origem            OPERACIONAL                        NaN
PCMONITORAMENTO         LOG VARCHAR2(4000)             Log registrado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*