# 📊 Tabela: PCECOMMERCEUNILEVERFILA

### Estrutura de Colunas e Restrições

                 Tabela     Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEUNILEVERFILA  CODFILIAL   VARCHAR2(2)                            Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEUNILEVERFILA     TABELA  VARCHAR2(50)              Nome da tabela a ser replicada    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEUNILEVERFILA         ID  VARCHAR2(50) RowID do registro da tabela a ser replicado    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEUNILEVERFILA DTINCLUSAO          DATE        Data de inclusão do registro na fila    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEUNILEVERFILA OBSERVACAO VARCHAR2(100)        Observação do registro a ser enviado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*