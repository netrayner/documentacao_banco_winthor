# 📊 Tabela: PCCONTROLECX

### Estrutura de Colunas e Restrições

      Tabela             Coluna Tipo/Tamanho                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTROLECX           CODBANCO  NUMBER(4,0)                              Campo para armazenar o número do caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLECX       CODFUNCCAIXA  NUMBER(8,0) Campo para armazenar o código do funcionário responsável pelo caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLECX         DTABERTURA         DATE             Campo para armazenar a data e hora de abertura do caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTROLECX       DTFECHAMENTO         DATE           Campo para armazenar a data e hora de fechamento do caixa.            OPERACIONAL                        NaN
PCCONTROLECX DTLIMITEFECHAMENTO         DATE  Campo para armazenar a data e hora limite para fechamento do caixa.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*