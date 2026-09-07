# 📊 Tabela: PCSPEDECFM500

### Estrutura de Colunas e Restrições

       Tabela              Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFM500              IDM010  NUMBER(8,0)                        ID da conta relacionada da parte B    CHAVE PRIMÁRIA (PK)              PCSPEDECFM010
PCSPEDECFM500         TIPOTRIBUTO      CHAR(1)                        I=Imposto de Renda Pessoa Jurídica            OPERACIONAL                        NaN
PCSPEDECFM500        SALDOINICIAL NUMBER(22,4)                         Saldo inicial da conta da parte B            OPERACIONAL                        NaN
PCSPEDECFM500      SALDOINICIALDC      CHAR(1)                              Sinal (D/C) do saldo inicial            OPERACIONAL                        NaN
PCSPEDECFM500   LANCAMENTOSPARTEA NUMBER(22,4)                           Lançamentos da conta na parte A            OPERACIONAL                        NaN
PCSPEDECFM500 LANCAMENTOSPARTEADC      CHAR(1)           Sinal (D/C) dos lançamentos da conta na parte A            OPERACIONAL                        NaN
PCSPEDECFM500   LANCAMENTOSPARTEB NUMBER(22,4)                           Lançamentos da conta na parte B            OPERACIONAL                        NaN
PCSPEDECFM500 LANCAMENTOSPARTEBDC      CHAR(1)           Sinal (D/C) dos lançamentos da conta na parte B            OPERACIONAL                        NaN
PCSPEDECFM500          SALDOFINAL NUMBER(22,4)                                     Saldo final calculado            OPERACIONAL                        NaN
PCSPEDECFM500        SALDOFINALDC      CHAR(1)                                Sinal (D/C) do saldo final            OPERACIONAL                        NaN
PCSPEDECFM500           CODFILIAL  VARCHAR2(2)                               Cód da filial do lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM500         TIPOPERIODO      CHAR(1)               T = período trimestral ou A = período anual    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM500         PERIODOLANC  NUMBER(2,0) 1 a 4 para período trimestral e 1 a 12 para período anual    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM500                 ANO  NUMBER(4,0)                                         Ano do lançamento    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFM500               LALUR      CHAR(1)                                     S = LALUR ou N = LACS    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*