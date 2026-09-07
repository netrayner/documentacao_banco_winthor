# 📊 Tabela: PCESTCRCOMPENSACAO

### Estrutura de Colunas e Restrições

            Tabela           Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTCRCOMPENSACAO              MES  VARCHAR2(2)              Mês do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO              ANO  VARCHAR2(4)              Ano do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO         CODBANCO  NUMBER(4,0)  Código do banco do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO         CODMOEDA  VARCHAR2(4)  Código da moeda do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO      VALORDEBITO NUMBER(14,2)  Valor de debito do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO     VALORCREDITO NUMBER(14,2) Valor de credito do saldo por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO DATASALDOINICIAL         DATE                     Data do saldo inicial            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO            SALDO NUMBER(14,2)               Saldo final por compensação            OPERACIONAL                        NaN
PCESTCRCOMPENSACAO     SALDOINICIAL NUMBER(14,2)             Saldo inicial por compensação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*