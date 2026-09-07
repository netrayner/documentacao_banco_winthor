# 📊 Tabela: PCPROVLANCTECHFIN

### Estrutura de Colunas e Restrições

           Tabela           Coluna  Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPROVLANCTECHFIN          CLIENTE   NUMBER(6,0)                      Codigo do Cliente            OPERACIONAL                        NaN
PCPROVLANCTECHFIN          NUMNOTA  NUMBER(10,0)                  Numero da Nota Fiscal            OPERACIONAL                        NaN
PCPROVLANCTECHFIN    NUMTRANSVENDA  NUMBER(10,0)           Numero da Transacao da Venda            OPERACIONAL                        NaN
PCPROVLANCTECHFIN         PRESTAPI   VARCHAR2(2)                    Numero da Prestacao            OPERACIONAL                        NaN
PCPROVLANCTECHFIN           RECNUM   NUMBER(8,0)      Numero de identificacao na PCLANC            OPERACIONAL                        NaN
PCPROVLANCTECHFIN            VALOR  NUMBER(12,2)                    Valor do Lancamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN             TIPO VARCHAR2(100)                     Tipo do Lancamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN     DTLANCAMENTO  TIMESTAMP(6)                     Data do Lancamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN          DTPAGTO  TIMESTAMP(6)                      Data do Pagamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN   TIPOLANCAMENTO VARCHAR2(100)                     Tipo do Lancamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN     TABELAORIGEM VARCHAR2(100)                       Tabela de Origem            OPERACIONAL                        NaN
PCPROVLANCTECHFIN           MOTIVO VARCHAR2(100)                   Motivo do Lancamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN            ERPID VARCHAR2(100)             ERPID do Lancamento na API            OPERACIONAL                        NaN
PCPROVLANCTECHFIN           DTLANC          DATE                     Data do lançamento            OPERACIONAL                        NaN
PCPROVLANCTECHFIN         CODCONTA  NUMBER(10,0)              Código da conta gerencial            OPERACIONAL                        NaN
PCPROVLANCTECHFIN        CODFILIAL   VARCHAR2(2)                       Codigo da filial            OPERACIONAL                        NaN
PCPROVLANCTECHFIN DTEXECUCAOCONCIL  TIMESTAMP(6) Data e hora da execução da conciliação            OPERACIONAL                        NaN
PCPROVLANCTECHFIN               ID  NUMBER(10,0)                          Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCPROVLANCTECHFIN    CONCILIACAOID  NUMBER(10,0)         Identificação da Conciliação\t            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*