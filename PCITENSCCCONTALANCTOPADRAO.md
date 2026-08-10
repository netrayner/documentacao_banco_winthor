# 📊 Tabela: PCITENSCCCONTALANCTOPADRAO

### Estrutura de Colunas e Restrições

                    Tabela            Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCITENSCCCONTALANCTOPADRAO     CODLANCPADRAO NUMBER(10,0)       Código do Lançamento Padrão    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSCCCONTALANCTOPADRAO          NATUREZA  VARCHAR2(1)            Natureza do Lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSCCCONTALANCTOPADRAO    CODREDUZIDO_PC NUMBER(10,0) Código Reduzido da Conta Contábil    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSCCCONTALANCTOPADRAO CODIGOCENTROCUSTO VARCHAR2(40)        Código do Centro de Custos    CHAVE PRIMÁRIA (PK)                        NaN
PCITENSCCCONTALANCTOPADRAO        PERCENTUAL NUMBER(10,6)              Percentual de Rateio            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*