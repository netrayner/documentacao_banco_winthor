# 📊 Tabela: PCVISITAFV

### Estrutura de Colunas e Restrições

    Tabela        Coluna   Tipo/Tamanho                                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVISITAFV     CODMOTIVO    NUMBER(6,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV          DATA           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV   HORAINICIAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV MINUTOINICIAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV     HORAFINAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV   MINUTOFINAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV       ASSUNTO VARCHAR2(4000)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV        CGCCLI   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV       CODUSUR    NUMBER(4,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV OBSERVACAO_PC VARCHAR2(4000)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV     IMPORTADO    NUMBER(1,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV    DTINCLUSAO           DATE                                                                                                               Grava Data e Hora da Última Importação.            OPERACIONAL                        NaN
PCVISITAFV        CODCLI    NUMBER(6,0) Codigo do cliente que será usado em conjunto com o campo cnpj para identificar o cliente no caso de ter no cadastro mais de um cliente com mesmo cnpj            OPERACIONAL                        NaN
PCVISITAFV   DTALTERACAO           DATE                                                                                                                         Data de Alteração no registro            OPERACIONAL                        NaN
PCVISITAFV       CODROTA    NUMBER(3,0)                                                                                                                                        Codigo da Rota            OPERACIONAL                        NaN
PCVISITAFV     LONGITUDE   VARCHAR2(20)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCVISITAFV      LATITUDE   VARCHAR2(20)                                                                                                                                                   NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*