# 📊 Tabela: PCCOTACAOSESI

### Estrutura de Colunas e Restrições

       Tabela        Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOTACAOSESI    CODCOTACAO NUMBER(10,0)                               Código da cotação.    CHAVE PRIMÁRIA (PK)                        NaN
PCCOTACAOSESI        CODCLI  NUMBER(6,0)                               Código do cliente.            OPERACIONAL                        NaN
PCCOTACAOSESI DTINIVALIDADE         DATE                      Data de inicio da validade.            OPERACIONAL                        NaN
PCCOTACAOSESI DTFIMVALIDADE         DATE                          Data final de validade.            OPERACIONAL                        NaN
PCCOTACAOSESI    DTRESPOSTA         DATE                     Data de resposta da cotação.            OPERACIONAL                        NaN
PCCOTACAOSESI      DTLIMITE         DATE                 Indica a data limite da cotação.            OPERACIONAL                        NaN
PCCOTACAOSESI    HORALIMITE  NUMBER(2,0)    Hora máxima que o arquivo pode ser exportado.            OPERACIONAL                        NaN
PCCOTACAOSESI  MINUTOLIMITE  NUMBER(2,0)  Minuto máximo que o arquivo pode ser exportado.            OPERACIONAL                        NaN
PCCOTACAOSESI    DTEXCLUSAO         DATE A data em que a cotação foi excluida do winthor.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*