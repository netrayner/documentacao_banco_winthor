# 📊 Tabela: PCSUGESTAODEVOLUCAO

### Estrutura de Colunas e Restrições

             Tabela               Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGESTAODEVOLUCAO NUMSUGESTAODEVOLUCAO   NUMBER(6,0) Código do número da sugestão de devolução    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAODEVOLUCAO                 DATA          DATE                           Data de criação            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO               CODCLI   NUMBER(6,0)                         Código do cliente            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO              NUMNOTA  NUMBER(10,0)                     Número da nota fiscal            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO              CODPROD   NUMBER(6,0)                         Código do produto            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO           QUANTIDADE  NUMBER(22,6)                      Quantidade devolvida            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO           OBSERVACAO VARCHAR2(100)                                Observação            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO         DTUTILIZACAO          DATE            Data de utilização da sugestão            OPERACIONAL                        NaN
PCSUGESTAODEVOLUCAO           CODUSUARIO   NUMBER(8,0) Código do usuário que utilizou a sugestão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*