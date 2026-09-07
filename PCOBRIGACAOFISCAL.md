# 📊 Tabela: PCOBRIGACAOFISCAL

### Estrutura de Colunas e Restrições

           Tabela                   Coluna   Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOBRIGACAOFISCAL             CODOBRFISCAL    NUMBER(6,0)                       Codigo obrigação fiscal    CHAVE PRIMÁRIA (PK)                        NaN
PCOBRIGACAOFISCAL            DESCOBRFISCAL   VARCHAR2(60)                 Descricao da obrigação fiscal            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL                     TIPO    VARCHAR2(1)                             Tipo da obrgiação            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL                       UF    VARCHAR2(2)                                            UF            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL                CODCIDADE    NUMBER(6,0)                           Cidade da obrigação            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL         CONSIDERADIAUTIL    VARCHAR2(1)                       Obrigação em dias uteis            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL      CONSIDERASABADOUTIL    VARCHAR2(1)                Considera sabado como dia util            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL           QTDIASLEMBRETE    NUMBER(3,0)               Lembrar apartir de quantos dias            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL              QTDIASAVISO    NUMBER(3,0) Enviar avisos com o intervalo de quantos dias            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL CONTINUALEMBRETEAPOSVENC    VARCHAR2(1)                     Lembrar após o vencimento            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL          DESCARTARAGENDA    VARCHAR2(1)                              Descartar agenda            OPERACIONAL                        NaN
PCOBRIGACAOFISCAL             OBSOBRFISCAL VARCHAR2(4000)                                           NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*