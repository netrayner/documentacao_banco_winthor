# 📊 Tabela: PCDIASUTEIS

### Estrutura de Colunas e Restrições

     Tabela        Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDIASUTEIS     CODFILIAL  VARCHAR2(2)                                 Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCDIASUTEIS          DATA         DATE             Indica a data afim de saber se ela é dia útil.    CHAVE PRIMÁRIA (PK)                        NaN
PCDIASUTEIS DIAFINANCEIRO  VARCHAR2(1) Campo para indicar se é um dia útil financeiro SIM ou NÃO.            OPERACIONAL                        NaN
PCDIASUTEIS     DIAVENDAS  VARCHAR2(1)     Campo para indicar se é um dia útil vendas SIM ou NÃO.            OPERACIONAL                        NaN
PCDIASUTEIS     NUMREGIAO  NUMBER(4,0)                            Numero da região dos dias uteis            OPERACIONAL                        NaN
PCDIASUTEIS       DIAROTA  VARCHAR2(1)       Campo para indicar se é um dia útil rota SIM ou NÃO.            OPERACIONAL                        NaN
PCDIASUTEIS    DTMXSALTER         DATE                                                        NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*