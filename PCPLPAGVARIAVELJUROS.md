# 📊 Tabela: PCPLPAGVARIAVELJUROS

### Estrutura de Colunas e Restrições

              Tabela            Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPLPAGVARIAVELJUROS          CODPLPAG  NUMBER(4,0)                              Código do plano de pagamento    CHAVE PRIMÁRIA (PK)                        NaN
PCPLPAGVARIAVELJUROS PRAZOMEDIOINICIAL  NUMBER(6,0)                                       Prazo Médio Inicial    CHAVE PRIMÁRIA (PK)                        NaN
PCPLPAGVARIAVELJUROS   PRAZOMEDIOFINAL  NUMBER(6,0)                                         Prazo Médio Final    CHAVE PRIMÁRIA (PK)                        NaN
PCPLPAGVARIAVELJUROS          PERCDESC NUMBER(18,6) Percentual de desconto/acréscimo referente ao prazo médio            OPERACIONAL                        NaN
PCPLPAGVARIAVELJUROS        DTMXSALTER         DATE                                                       NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*