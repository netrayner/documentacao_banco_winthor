# 📊 Tabela: PCREDECLIENTE

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREDECLIENTE       CODREDE  NUMBER(4,0)                         Indica o código da rede.    CHAVE PRIMÁRIA (PK)                        NaN
PCREDECLIENTE     DESCRICAO VARCHAR2(60)                      Indica a descrição da rede.            OPERACIONAL                        NaN
PCREDECLIENTE    DTCADASTRO         DATE               Indica a data de cadastro da rede.            OPERACIONAL                        NaN
PCREDECLIENTE    CODFUNCCAD  NUMBER(8,0)    Indica o funcionario que cadastrou o cliente.            OPERACIONAL                        NaN
PCREDECLIENTE      DTULTALT         DATE               Indica a data da última alteração.            OPERACIONAL                        NaN
PCREDECLIENTE CODFUNCULTALT  NUMBER(8,0) Indica o funcionario que fez a ultima alteração.            OPERACIONAL                        NaN
PCREDECLIENTE    DTMXSALTER         DATE                                              NaN            OPERACIONAL                        NaN
PCREDECLIENTE DATAALTERACAO         DATE         Indica a data que a tabela foi alterada             OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*