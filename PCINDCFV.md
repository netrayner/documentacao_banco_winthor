# 📊 Tabela: PCINDCFV

### Estrutura de Colunas e Restrições

  Tabela        Coluna   Tipo/Tamanho                                                                                                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINDCFV    CODINDENIZ   NUMBER(10,0)                                                                                                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCINDCFV          DATA           DATE                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV        CGCCLI   VARCHAR2(18)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV     CODFILIAL    VARCHAR2(2)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV     NUMPEDRCA   NUMBER(10,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV   TIPOINDENIZ    VARCHAR2(1)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV       CODUSUR    NUMBER(4,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV           OBS   VARCHAR2(80)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV OBSERVACAO_PC VARCHAR2(4000)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV     IMPORTADO    NUMBER(1,0)                                                                                                                                                   NaN            OPERACIONAL                        NaN
PCINDCFV    DTINCLUSAO           DATE                                                                                                               Grava Data e Hora da Última Importação.            OPERACIONAL                        NaN
PCINDCFV        CODCLI    NUMBER(6,0) Codigo do cliente que será usado em conjunto com o campo cnpj para identificar o cliente no caso de ter no cadastro mais de um cliente com mesmo cnpj            OPERACIONAL                        NaN
PCINDCFV   DTALTERACAO           DATE                                                                                                                         Data de Alteração no registro            OPERACIONAL                        NaN
PCINDCFV    NUMINDENIZ   NUMBER(10,0)                                                                                                              Número da indenização gravada na pcindc.            OPERACIONAL                        NaN
PCINDCFV       RETORNO    NUMBER(4,0)                                                                                                              Flag utilizado pelos fornecedores de FV.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*