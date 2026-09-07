# 📊 Tabela: PCGONDOLAFV

### Estrutura de Colunas e Restrições

     Tabela        Coluna   Tipo/Tamanho                                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGONDOLAFV     IMPORTADO    NUMBER(1,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV   NUMCONTAGEM    NUMBER(8,0)                                                                                                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGONDOLAFV    DTCONTAGEM           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV       CODUSUR    NUMBER(4,0)                                                                                                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGONDOLAFV        CGCCLI   VARCHAR2(18)                                                                                                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGONDOLAFV       CODCONC    VARCHAR2(4)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV   HORAINICIAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV     HORAFINAL    NUMBER(2,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV OBSERVACAO_PC VARCHAR2(4000)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV    DTINCLUSAO           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCGONDOLAFV        CODCLI    NUMBER(6,0) Codigo do cliente que será usado em conjunto com o campo cnpj para identificar o cliente no caso de ter no cadastro mais de um cliente com mesmo cnpj            OPERACIONAL                        NaN
PCGONDOLAFV   DTALTERACAO           DATE                                                                                                                         Data de Alteração no registro            OPERACIONAL                        NaN
PCGONDOLAFV     NUMVISITA   NUMBER(10,0)                                                                                                                                      Numero da visita            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*