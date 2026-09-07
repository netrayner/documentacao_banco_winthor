# 📊 Tabela: PCGRUPOFIDELIDADE

### Estrutura de Colunas e Restrições

           Tabela             Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGRUPOFIDELIDADE CODGRUPOFIDELIDADE   NUMBER(9,0)              Código Identificador do grupo de Fidelidade    CHAVE PRIMÁRIA (PK)                        NaN
PCGRUPOFIDELIDADE    GRUPOFIDELIDADE VARCHAR2(200)                         Descrição do Grupo de Fidelidade            OPERACIONAL                        NaN
PCGRUPOFIDELIDADE    UTILIZACASHBACK   VARCHAR2(1) Flag para informar se grupo utiliza processo de cashback            OPERACIONAL                        NaN
PCGRUPOFIDELIDADE          DTALTERC5  TIMESTAMP(6)                                        Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*