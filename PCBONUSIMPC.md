# 📊 Tabela: PCBONUSIMPC

### Estrutura de Colunas e Restrições

     Tabela       Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBONUSIMPC     NUMBONUS  NUMBER(6,0)               Numero do Bonus    CHAVE PRIMÁRIA (PK)                        NaN
PCBONUSIMPC     QTPEDIDO  NUMBER(6,0)          Quantidade do pedido            OPERACIONAL                        NaN
PCBONUSIMPC   VALORTOTAL NUMBER(14,2)          Valor Total do Bonus            OPERACIONAL                        NaN
PCBONUSIMPC    PESOTOTAL NUMBER(14,2)           Peso Total do Bonus            OPERACIONAL                        NaN
PCBONUSIMPC CODFUNCBONUS  NUMBER(8,0)   Funcionario que Fez o Bonus            OPERACIONAL                        NaN
PCBONUSIMPC    CODFILIAL  VARCHAR2(2)                        Filial            OPERACIONAL                        NaN
PCBONUSIMPC   DTMONTAGEM         DATE              Data da Montagem            OPERACIONAL                        NaN
PCBONUSIMPC   OBSERVACAO VARCHAR2(40)           Observação do bonus            OPERACIONAL                        NaN
PCBONUSIMPC      EMITIDO  VARCHAR2(1)         Se foi emitido ou não            OPERACIONAL                        NaN
PCBONUSIMPC     DTCANCEL         DATE Data do Cancelamento do Bonus            OPERACIONAL                        NaN
PCBONUSIMPC      DTFECHA         DATE   Data do Fechamento do Bonus            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*