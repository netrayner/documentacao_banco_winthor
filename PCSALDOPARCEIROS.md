# 📊 Tabela: PCSALDOPARCEIROS

### Estrutura de Colunas e Restrições

          Tabela              Coluna Tipo/Tamanho                                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDOPARCEIROS           CODFILIAL  VARCHAR2(2)                                                Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS       CODPLANOCONTA  NUMBER(5,0)               Código do plano de contas utilizado no exercício.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS                 MES  NUMBER(2,0)                              Mês referente ao saldo consolidado    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS                 ANO  NUMBER(4,0)                              Ano referente ao saldo consolidado    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS      CODREDUZIDO_PC VARCHAR2(12)                                       Código da conta do plano.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS         CODPARCEIRO NUMBER(10,0)                        Código referente ao parceiro do gestão.     CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS        TIPOPARCEIRO  VARCHAR2(1) Define qual o tipo do parceiro; fornecedor, RCA, cliente e etc.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOPARCEIROS         VALORDEBITO NUMBER(22,2)                                                Valor de débito             OPERACIONAL                        NaN
PCSALDOPARCEIROS        VALORCREDITO NUMBER(22,2)                                                Valor de crédito            OPERACIONAL                        NaN
PCSALDOPARCEIROS  VLRDEBENCERRAMENTO NUMBER(22,2)                              Valor débito antes do encerramento            OPERACIONAL                        NaN
PCSALDOPARCEIROS VLRCREDENCERRAMENTO NUMBER(22,2)                             Valor crédito antes do encerramento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*