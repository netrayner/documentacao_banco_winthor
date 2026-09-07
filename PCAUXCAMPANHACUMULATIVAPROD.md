# 📊 Tabela: PCAUXCAMPANHACUMULATIVAPROD

### Estrutura de Colunas e Restrições

                     Tabela         Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAUXCAMPANHACUMULATIVAPROD             ID NUMBER(20,0)                                                           Identificador do registro na tabela.    CHAVE PRIMÁRIA (PK)                        NaN
PCAUXCAMPANHACUMULATIVAPROD           DATA         DATE                                                                    Data do registro na tabela.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD         NUMPED NUMBER(10,0)                                                       Número do pedido que recebeu a campanha.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD        CODPROD  NUMBER(6,0)                                                      Código do produto que recebeu a campanha.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD         NUMSEQ NUMBER(20,0)                                 Número do sequencial do item no pedido que recebeu a campanha.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD    NUMCAMPANHA  NUMBER(8,0)                                         Número da campanha de verba cadastrada na rotina 1801.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD     VLCAMPANHA NUMBER(18,6)                                            Valor da campanha de verba encontrado na validação.            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD ORIGEMCAMPANHA  NUMBER(6,0) Número da rotina cuja a campanha de verba foi vinculada(1831,301, 357, 561, 3306, 3307, 3320).            OPERACIONAL                        NaN
PCAUXCAMPANHACUMULATIVAPROD PERCCUSTFORNEC NUMBER(18,6)                                                             Percentual do custo do fornecedor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*