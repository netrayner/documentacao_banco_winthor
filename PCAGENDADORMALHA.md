# 📊 Tabela: PCAGENDADORMALHA

### Estrutura de Colunas e Restrições

          Tabela              Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAGENDADORMALHA   CODAGENDADORMALHA  NUMBER(10,0)               Identificador da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCAGENDADORMALHA           DESCRICAO VARCHAR2(250)                    Descrição da malha            OPERACIONAL                        NaN
PCAGENDADORMALHA DATAVIGENCIAINICIAL  TIMESTAMP(6) Data de inicio para execução da malha            OPERACIONAL                        NaN
PCAGENDADORMALHA   DATAVIGENCIAFINAL  TIMESTAMP(6)    Data limite para execução da malha            OPERACIONAL                        NaN
PCAGENDADORMALHA       CRIADOSISTEMA   VARCHAR2(1)            Malha criada pelo sistema.            OPERACIONAL                        NaN
PCAGENDADORMALHA       LIMITEPERIODO   VARCHAR2(1)                     Limite de período            OPERACIONAL                        NaN
PCAGENDADORMALHA        TIPOEXECUCAO   VARCHAR2(1)                      Tipo da execução            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*