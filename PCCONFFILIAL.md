# 📊 Tabela: PCCONFFILIAL

### Estrutura de Colunas e Restrições

      Tabela               Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFFILIAL            CODCONFIG  NUMBER(6,0)                                  NaN            OPERACIONAL                        NaN
PCCONFFILIAL                  ANO  NUMBER(4,0)                                  NaN            OPERACIONAL                        NaN
PCCONFFILIAL       CODGRUPOFILIAL  NUMBER(5,0)                                  NaN            OPERACIONAL                        NaN
PCCONFFILIAL            CODFILIAL  VARCHAR2(2)                                  NaN            OPERACIONAL                        NaN
PCCONFFILIAL          BLOQJANEIRO  VARCHAR2(1)             Bloqueia mês de Janeiro.            OPERACIONAL                        NaN
PCCONFFILIAL        BLOQFEVEREIRO  VARCHAR2(1)           Bloqueia mês de Fevereiro.            OPERACIONAL                        NaN
PCCONFFILIAL            BLOQMARCO  VARCHAR2(1)               Bloqueia mês de Março.            OPERACIONAL                        NaN
PCCONFFILIAL            BLOQABRIL  VARCHAR2(1)               Bloqueia mês de Abril.            OPERACIONAL                        NaN
PCCONFFILIAL             BLOQMAIO  VARCHAR2(1)                Bloqueia mês de Maio.            OPERACIONAL                        NaN
PCCONFFILIAL            BLOQJUNHO  VARCHAR2(1)               Bloqueia mês de Junho.            OPERACIONAL                        NaN
PCCONFFILIAL            BLOQJULHO  VARCHAR2(1)               Bloqueia mês de Julho.            OPERACIONAL                        NaN
PCCONFFILIAL           BLOQAGOSTO  VARCHAR2(1)              Bloqueia mês de Agosto.            OPERACIONAL                        NaN
PCCONFFILIAL         BLOQSETEMBRO  VARCHAR2(1)            Bloqueia mês de Setembro.            OPERACIONAL                        NaN
PCCONFFILIAL          BLOQOUTUBRO  VARCHAR2(1)             Bloqueia mês de Outubro.            OPERACIONAL                        NaN
PCCONFFILIAL         BLOQNOVEMBRO  VARCHAR2(1)            Bloqueia mês de Novembro.            OPERACIONAL                        NaN
PCCONFFILIAL         BLOQDEZEMBRO  VARCHAR2(1)            Bloqueia mês de Dezembro.            OPERACIONAL                        NaN
PCCONFFILIAL     CODCONFEXERCICIO  NUMBER(8,0)                  Código do Exercício            OPERACIONAL                        NaN
PCCONFFILIAL    DTINICIOEXERCICIO         DATE Data de Início do Exercício Contábil            OPERACIONAL                        NaN
PCCONFFILIAL       DTFIMEXERCICIO         DATE    Data de Fim do Exercício Contábil            OPERACIONAL                        NaN
PCCONFFILIAL     SITUACAOESPECIAL  NUMBER(8,0)       Situação especial do exercício            OPERACIONAL                        NaN
PCCONFFILIAL DATASITUACAOESPECIAL         DATE            Data da situação especial            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*