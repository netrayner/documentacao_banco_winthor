# 📊 Tabela: PCMOVETAPA

### Estrutura de Colunas e Restrições

    Tabela           Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVETAPA            NUMOP   NUMBER(8,0)                Número da Ordem de Produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVETAPA              OBS VARCHAR2(200)         Observação da movimentada da etapa.            OPERACIONAL                        NaN
PCMOVETAPA         CODETAPA   NUMBER(6,0)      Código da etapa utilizada na produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVETAPA        CODFILIAL   VARCHAR2(2)               Código da filial da produção.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVETAPA         DTINICIO          DATE                Data Inicio da Movimentação.            OPERACIONAL                        NaN
PCMOVETAPA            DTFIM          DATE                 Data Final da movimentação.            OPERACIONAL                        NaN
PCMOVETAPA         SITUACAO   VARCHAR2(1)          Situação da Etapa na movimentação.            OPERACIONAL                        NaN
PCMOVETAPA         DTCANCEL          DATE       Data do Cancelamento da Movimentação.            OPERACIONAL                        NaN
PCMOVETAPA    CODFUNCCANCEL   NUMBER(8,0)    Funcionario que realizou o cancelamento.            OPERACIONAL                        NaN
PCMOVETAPA      CODFUNCLANC   NUMBER(8,0)       Funcionario que lancou a movimetação.            OPERACIONAL                        NaN
PCMOVETAPA DTPREVISAOINICIO          DATE   Data e Hora em que a etapa será iniciada.            OPERACIONAL                        NaN
PCMOVETAPA  DTPREVISAOFINAL          DATE Data e Hora em que a etapa será finalizada.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*