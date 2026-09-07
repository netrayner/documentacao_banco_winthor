# 📊 Tabela: PCFAIXASCONTABEIS

### Estrutura de Colunas e Restrições

           Tabela           Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFAIXASCONTABEIS CODFAIXACONTABIL NUMBER(10,0)                            Código da faixa contabil    CHAVE PRIMÁRIA (PK)                        NaN
PCFAIXASCONTABEIS        DESCRICAO VARCHAR2(80)                         Descrição da faixa contabil            OPERACIONAL                        NaN
PCFAIXASCONTABEIS       VALORMENOR NUMBER(18,2)                  Valor que indica prejuizo da faixa            OPERACIONAL                        NaN
PCFAIXASCONTABEIS    VALORINTERINI NUMBER(18,2) Valor que indica o valor inicial da faixa aceitavel            OPERACIONAL                        NaN
PCFAIXASCONTABEIS    VALORINTERFIM NUMBER(18,2)   Valor que indica o valor final da faixa aceitavel            OPERACIONAL                        NaN
PCFAIXASCONTABEIS       VALORMAIOR NUMBER(18,2)   Valor que indica o começo do valor ideal da faixa            OPERACIONAL                        NaN
PCFAIXASCONTABEIS           STATUS  VARCHAR2(2)     Status que indica se a faixa está ativa ou não.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*