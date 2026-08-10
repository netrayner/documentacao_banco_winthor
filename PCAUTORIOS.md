# 📊 Tabela: PCAUTORIOS

### Estrutura de Colunas e Restrições

    Tabela       Coluna Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUTORIOS    CODTIPOOS  NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCAUTORIOS    CODFUNCAO  NUMBER(4,0)                                NaN            OPERACIONAL                        NaN
PCAUTORIOS    MATRICULA  VARCHAR2(8) Indica a matricula do funcionario.            OPERACIONAL                        NaN
PCAUTORIOS CODIGOPERFIL NUMBER(20,0)                                NaN            OPERACIONAL                        NaN
PCAUTORIOS   PRIORIDADE  NUMBER(4,0) Prioridade de execução - Vocollect            OPERACIONAL                        NaN
PCAUTORIOS CODROTINAEXE  VARCHAR2(4)     rotina de execução - Vocollect            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*