# 📊 Tabela: PCSERVICOCLIENTECNAE

### Estrutura de Colunas e Restrições

              Tabela     Coluna  Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTECNAE    CODCNAE  NUMBER(10,0)                               Código identificador do cnae    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOCLIENTECNAE  DESCRICAO VARCHAR2(255)                                          Descrição do cnae            OPERACIONAL                        NaN
PCSERVICOCLIENTECNAE   PRIMARIO       CHAR(1) Se o cnae é primário, será igual a "S". Caso contrário "N"            OPERACIONAL                        NaN
PCSERVICOCLIENTECNAE CODCLIENTE  NUMBER(10,0)                            Código identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTECNAE     NUMERO  VARCHAR2(50)                                             Numero do cnae            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*