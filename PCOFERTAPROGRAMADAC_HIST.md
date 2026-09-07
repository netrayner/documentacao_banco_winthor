# 📊 Tabela: PCOFERTAPROGRAMADAC_HIST

### Estrutura de Colunas e Restrições

                  Tabela           Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOFERTAPROGRAMADAC_HIST        DATAALTER          DATE                   Data de alteração            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST        CODFILIAL   VARCHAR2(2)                    Código da Filial            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST        CODOFERTA   NUMBER(6,0)                    Código da Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST       DESCOFERTA  VARCHAR2(60)                 Descrição da Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST        DTINICIAL          DATE              Data inicial da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST          DTFINAL          DATE                Data final da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST         DTCANCEL          DATE      Data do cancelamento da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST     MOTIVOCANCEL  VARCHAR2(80)              Motivo do Cancelamento            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST    CODFUNCCANCEL   NUMBER(8,0)     Código funcionário cancelamento            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST           DTORIG          DATE                 Data criação oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST      CODFUNCORIG   NUMBER(8,0)         Código funcionário cadastro            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST   DTULTALTOFERTA          DATE        Data última alteração oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST    CODFUNCULTALT   NUMBER(8,0) Código funcionário ultima alteração            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST      HORAINICIAL          DATE              Hora inicial da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST        HORAFINAL          DATE                Hora final da oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST   VALIDACONVENIO   VARCHAR2(1)                     Valida Convênio            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST    CODTIPOOFERTA   NUMBER(6,0)                  Código tipo oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST  CODOFERTAORIGEM   NUMBER(6,0)                Código oferta origem            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST   CODPRECOOFERTA   NUMBER(6,0)                 Código Preco oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST PRIORIDADEOFERTA   NUMBER(2,0)                   Prioridade Oferta            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST       COMPUTADOR VARCHAR2(150)         Computador Origem Alteração            OPERACIONAL                        NaN
PCOFERTAPROGRAMADAC_HIST        DTALTERC5  TIMESTAMP(6)                      Data alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*