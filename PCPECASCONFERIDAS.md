# 📊 Tabela: PCPECASCONFERIDAS

### Estrutura de Colunas e Restrições

           Tabela    Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPECASCONFERIDAS   CODPROD  NUMBER(6,0)          Código produto            OPERACIONAL                        NaN
PCPECASCONFERIDAS     NUMOS NUMBER(10,0)          Número da O.S.            OPERACIONAL                        NaN
PCPECASCONFERIDAS      PESO NUMBER(20,8)            Peso da peça            OPERACIONAL                        NaN
PCPECASCONFERIDAS   USUARIO  NUMBER(8,0)     Usuário de inclusão            OPERACIONAL                        NaN
PCPECASCONFERIDAS      DATA         DATE      Data incrementação            OPERACIONAL                        NaN
PCPECASCONFERIDAS    ROTINA VARCHAR2(10)                  Rotina            OPERACIONAL                        NaN
PCPECASCONFERIDAS   NUMLOTE VARCHAR2(15) Número lote caso exista            OPERACIONAL                        NaN
PCPECASCONFERIDAS ORDEMLANC  NUMBER(8,0)     Ordem de lançamento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*