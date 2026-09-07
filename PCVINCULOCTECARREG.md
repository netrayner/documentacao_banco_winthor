# 📊 Tabela: PCVINCULOCTECARREG

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVINCULOCTECARREG     CODVINCULO NUMBER(10,0)                                                  Chave do vinculo CTe Carregamento            OPERACIONAL                        NaN
PCVINCULOCTECARREG NUMTRANSENTCTE NUMBER(10,0)                                               Numtransent do CTE que foi vinculado    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOCTECARREG     VLTOTALCTE NUMBER(12,2)                                                             Valor do CTE vinculado            OPERACIONAL                        NaN
PCVINCULOCTECARREG         NUMCAR  NUMBER(8,0)                                                   Número do carregamento vinculado    CHAVE PRIMÁRIA (PK)                        NaN
PCVINCULOCTECARREG     VLTOTALCAR NUMBER(14,2)                                                        Valor total do carregamento            OPERACIONAL                        NaN
PCVINCULOCTECARREG       VALIDADO  VARCHAR2(1) Quando N informa que o vinculo não foi validado, S informa que houve uma validação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*