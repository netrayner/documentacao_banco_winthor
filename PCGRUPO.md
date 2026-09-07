# 📊 Tabela: PCGRUPO

### Estrutura de Colunas e Restrições

 Tabela                Coluna Tipo/Tamanho                                                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPO              CODGRUPO  NUMBER(4,0)                                                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCGRUPO                 GRUPO VARCHAR2(40)                                                                                      NaN            OPERACIONAL                        NaN
PCGRUPO RESTRINGIRNOBALANCETE  VARCHAR2(1) Campo que define a restricao de apresentacao do grupo de conta no balancete (rotina 124)            OPERACIONAL                        NaN
PCGRUPO      USACONTACONTABIL  VARCHAR2(1)        Campo que define se será obrigatório informar conta contábil na criação da conta.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*