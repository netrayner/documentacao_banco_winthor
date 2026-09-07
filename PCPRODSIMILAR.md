# 📊 Tabela: PCPRODSIMILAR

### Estrutura de Colunas e Restrições

       Tabela           Coluna Tipo/Tamanho                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODSIMILAR        CODFILIAL  VARCHAR2(2)                                                 Código da filial .            OPERACIONAL                        NaN
PCPRODSIMILAR    CODPRODMASTER  NUMBER(6,0)                                          Código do Produto Master.            OPERACIONAL                        NaN
PCPRODSIMILAR CODPRODPRINCIPAL  NUMBER(6,0)                                       Código do Produto Principal.            OPERACIONAL                        NaN
PCPRODSIMILAR   CODPRODSIMILAR  NUMBER(6,0)                                         Código do Produto Similar.            OPERACIONAL                        NaN
PCPRODSIMILAR         NUMORDEM  NUMBER(3,0) Define a prioridade da produção no caso de troca de Matéria Prima.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*