# 📊 Tabela: PCALCADACONTAGENCIAL

### Estrutura de Colunas e Restrições

              Tabela        Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADACONTAGENCIAL     CODFILIAL  VARCHAR2(2)               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGENCIAL      CODCONTA  NUMBER(6,0)      Código da conta gerencial    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGENCIAL     CODAUTOR1  NUMBER(8,0)        Código do autorizante 1    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGENCIAL     CODAUTOR2  NUMBER(8,0)        Código do autorizante 2    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADACONTAGENCIAL      VLLIMITE NUMBER(22,6)                Valor do limite            OPERACIONAL                        NaN
PCALCADACONTAGENCIAL CODUSUARIOINC  NUMBER(8,0)  Código do usuário que incluiu            OPERACIONAL                        NaN
PCALCADACONTAGENCIAL    DTINCLUSAO         DATE Data de inclusão do lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*