# 📊 Tabela: PCEQUIPAMENTOSAT

### Estrutura de Colunas e Restrições

          Tabela          Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEQUIPAMENTOSAT          NUMSAT  NUMBER(4,0)          Número de cadastro de SAT            OPERACIONAL                        NaN
PCEQUIPAMENTOSAT        NUMSERIE VARCHAR2(13)    Número de série equipamento SAT    CHAVE PRIMÁRIA (PK)                        NaN
PCEQUIPAMENTOSAT           MARCA VARCHAR2(20)              Marca equipamento SAT    CHAVE PRIMÁRIA (PK)                        NaN
PCEQUIPAMENTOSAT          MODELO VARCHAR2(20)             Modelo equipamento SAT            OPERACIONAL                        NaN
PCEQUIPAMENTOSAT          VERSAO VARCHAR2(20)             Versão equipamento SAT            OPERACIONAL                        NaN
PCEQUIPAMENTOSAT     CODATIVACAO VARCHAR2(20) Código de ativação equipamento SAT            OPERACIONAL                        NaN
PCEQUIPAMENTOSAT TIPOEQUIPAMENTO  VARCHAR2(3)                Tipo de Equipamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*