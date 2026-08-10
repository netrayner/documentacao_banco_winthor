# 📊 Tabela: PCEVENTOSCTE

### Estrutura de Colunas e Restrições

      Tabela             Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEVENTOSCTE             CODIGO  NUMBER(10,0) Sequencial chave dos eventos do CTe    CHAVE PRIMÁRIA (PK)                        NaN
PCEVENTOSCTE           CHAVECTE  VARCHAR2(44)                        Chave do CTe            OPERACIONAL                        NaN
PCEVENTOSCTE        DTEVENTOCTE          DATE               Momento do evento CTe            OPERACIONAL                        NaN
PCEVENTOSCTE    PROTOCOLOEVENTO  VARCHAR2(20)       Número do protocolo do evento            OPERACIONAL                        NaN
PCEVENTOSCTE DESCRICAOEVENTOCTE VARCHAR2(256)          Descrição do evento do CTe            OPERACIONAL                        NaN
PCEVENTOSCTE        NUMTRANSENT  NUMBER(10,0)          Número de transação do CTe            OPERACIONAL                        NaN
PCEVENTOSCTE          CODFILIAL   VARCHAR2(2)                    Código da Filial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*