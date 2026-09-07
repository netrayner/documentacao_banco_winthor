# 📊 Tabela: PCRECFUNCFV

### Estrutura de Colunas e Restrições

     Tabela        Coluna   Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECFUNCFV     IMPORTADO    NUMBER(1,0)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV   CODFUNCDEST    NUMBER(8,0)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV       ASSUNTO  VARCHAR2(100)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV   TEXTORECADO VARCHAR2(4000)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV   NUMRECADOFV   NUMBER(12,0)                                     NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCRECFUNCFV       CODUSUR    NUMBER(4,0)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV OBSERVACAO_PC VARCHAR2(4000)                                     NaN            OPERACIONAL                        NaN
PCRECFUNCFV    DTINCLUSAO           DATE Grava Data e Hora da Última Importação.            OPERACIONAL                        NaN
PCRECFUNCFV   DTALTERACAO           DATE           Data de Alteração no registro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*