# 📊 Tabela: PCMENSAGEMORCAMENTO

### Estrutura de Colunas e Restrições

             Tabela        Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMORCAMENTO   CODMENSAGEM   NUMBER(4,0)            Código da mensagem    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMORCAMENTO      MENSAGEM VARCHAR2(500)         Descrição da mensagem            OPERACIONAL                        NaN
PCMENSAGEMORCAMENTO    DTINCLUSAO          DATE              Data de inclusão            OPERACIONAL                        NaN
PCMENSAGEMORCAMENTO CODUSUARIOINC   NUMBER(8,0) Código do usuário que incluiu            OPERACIONAL                        NaN
PCMENSAGEMORCAMENTO   DTALTERACAO          DATE             Data de alteração            OPERACIONAL                        NaN
PCMENSAGEMORCAMENTO CODUSUARIOALT   NUMBER(8,0) Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*