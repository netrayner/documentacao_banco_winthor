# 📊 Tabela: PCDISPROTA

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDISPROTA      CODDISP  NUMBER(5,0) Código de disponibilidade de rota.            OPERACIONAL                        NaN
PCDISPROTA      CODROTA  NUMBER(4,0)                    Código da rota.            OPERACIONAL                        NaN
PCDISPROTA    CODFILIAL  VARCHAR2(2)                  Código da filial.            OPERACIONAL                        NaN
PCDISPROTA TURNOENTREGA  VARCHAR2(5)                Turno para entrega.            OPERACIONAL                        NaN
PCDISPROTA   CAPACIDADE NUMBER(18,3)                Capacidade da rota.            OPERACIONAL                        NaN
PCDISPROTA         DATA         DATE                   Data de entrega.            OPERACIONAL                        NaN
PCDISPROTA DIASROTADISP  NUMBER(3,0)                     DIAS ROTA DISP            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*