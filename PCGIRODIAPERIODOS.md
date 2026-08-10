# 📊 Tabela: PCGIRODIAPERIODOS

### Estrutura de Colunas e Restrições

           Tabela        Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGIRODIAPERIODOS    CODPERIODO   NUMBER(6,0)               Código do período    CHAVE PRIMÁRIA (PK)                        NaN
PCGIRODIAPERIODOS     DESCRICAO VARCHAR2(100)            Descrição do período            OPERACIONAL                        NaN
PCGIRODIAPERIODOS       NUMDIAS   NUMBER(6,0)                  Número de dias            OPERACIONAL                        NaN
PCGIRODIAPERIODOS    DTCADASTRO          DATE                Data de cadastro            OPERACIONAL                        NaN
PCGIRODIAPERIODOS CODUSUARIOCAD   NUMBER(8,0) Código do usuário que cadastrou            OPERACIONAL                        NaN
PCGIRODIAPERIODOS   DTALTERACAO          DATE               Data de alteração            OPERACIONAL                        NaN
PCGIRODIAPERIODOS CODUSUARIOALT   NUMBER(8,0)   Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*