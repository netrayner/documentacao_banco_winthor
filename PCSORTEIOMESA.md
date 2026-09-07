# 📊 Tabela: PCSORTEIOMESA

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSORTEIOMESA             MESA NUMBER(10,0)                Nro da mesa sorteada            OPERACIONAL                        NaN
PCSORTEIOMESA           CODCLI NUMBER(10,0)  Código do cliente da mesa sorteada            OPERACIONAL                        NaN
PCSORTEIOMESA    DTHORASORTEIO         DATE  Data/Hora da realização do sorteio            OPERACIONAL                        NaN
PCSORTEIOMESA DTHORAREALIZACAO         DATE Data/Hora da Realização da Pesquisa            OPERACIONAL                        NaN
PCSORTEIOMESA         SITUACAO  VARCHAR2(1)                Situação da Pesquisa            OPERACIONAL                        NaN
PCSORTEIOMESA          NUMORCA NUMBER(20,0)            Nro do orçamento da mesa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*