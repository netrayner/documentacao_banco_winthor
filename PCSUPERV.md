# 📊 Tabela: PCSUPERV

### Estrutura de Colunas e Restrições

  Tabela            Coluna  Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUPERV     CODSUPERVISOR   NUMBER(4,0)                            NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSUPERV              NOME  VARCHAR2(40)                            NaN            OPERACIONAL                        NaN
PCSUPERV          REGIONAL   NUMBER(2,0)                            NaN            OPERACIONAL                        NaN
PCSUPERV        COD_CADRCA   NUMBER(4,0)                            NaN            OPERACIONAL                        NaN
PCSUPERV           POSICAO   VARCHAR2(1)                            NaN            OPERACIONAL                        NaN
PCSUPERV PERCPARTVENDAPREV   NUMBER(8,4)                            NaN            OPERACIONAL                        NaN
PCSUPERV    PERCMARGEMPREV   NUMBER(8,4)                            NaN            OPERACIONAL                        NaN
PCSUPERV        CODGERENTE   NUMBER(4,0)                            NaN            OPERACIONAL                        NaN
PCSUPERV    TIPOSUPERVISOR   VARCHAR2(1)                            NaN            OPERACIONAL                        NaN
PCSUPERV       PERCOMISSAO   NUMBER(4,2)                            NaN            OPERACIONAL                        NaN
PCSUPERV        DTADMISSAO          DATE                            NaN            OPERACIONAL                        NaN
PCSUPERV        DTDEMISSAO          DATE      Indica a data de emissão.            OPERACIONAL                        NaN
PCSUPERV               CPF  VARCHAR2(20)        Indica o numero do CPF.            OPERACIONAL                        NaN
PCSUPERV    CODCOORDENADOR  NUMBER(10,0) Indica o Coordenador de venda.            OPERACIONAL                        NaN
PCSUPERV             EMAIL VARCHAR2(100)            Email do supervisor            OPERACIONAL                        NaN
PCSUPERV        VLCORRENTE  NUMBER(22,6)        Valor do conta corrente            OPERACIONAL                        NaN
PCSUPERV         VLLIMCRED  NUMBER(22,6)     Valor do limite do crédito            OPERACIONAL                        NaN
PCSUPERV        USADEBCRED   VARCHAR2(1)           Usa débito e crédito            OPERACIONAL                        NaN
PCSUPERV        DTMXSALTER          DATE                            NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*