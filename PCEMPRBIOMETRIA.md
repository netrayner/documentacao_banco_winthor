# 📊 Tabela: PCEMPRBIOMETRIA

### Estrutura de Colunas e Restrições

         Tabela           Coluna Tipo/Tamanho  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMPRBIOMETRIA        MATRICULA  NUMBER(8,0) Matrícula do Usuário    CHAVE PRIMÁRIA (PK)                     PCEMPR
PCEMPRBIOMETRIA        CODFILIAL  VARCHAR2(2)     Código da Filial    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCEMPRBIOMETRIA    MODELO_LEITOR VARCHAR2(30)     Modelo do leitor    CHAVE PRIMÁRIA (PK)                        NaN
PCEMPRBIOMETRIA   DIGITALPOLEGAR         BLOB      Digital polegar            OPERACIONAL                        NaN
PCEMPRBIOMETRIA DIGITALINDICADOR         BLOB    Digital indicador            OPERACIONAL                        NaN
PCEMPRBIOMETRIA     DIGITALMEDIO         BLOB        Digital médio            OPERACIONAL                        NaN
PCEMPRBIOMETRIA    DIGITALANELAR         BLOB       Digital anelar            OPERACIONAL                        NaN
PCEMPRBIOMETRIA    DIGITALMINIMO         BLOB       Digital mínimo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*