# 📊 Tabela: PCCENTROCUSTO

### Estrutura de Colunas e Restrições

       Tabela                    Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCENTROCUSTO                 DESCRICAO VARCHAR2(40)                            Descrição do Centro de Custo.            OPERACIONAL                        NaN
PCCENTROCUSTO            CODCENTROCUSTO VARCHAR2(40)                                                      NaN            OPERACIONAL                        NaN
PCCENTROCUSTO             RECEBE_LANCTO  VARCHAR2(1) Indica se o Nível do Centro de custos recebe lançamentos            OPERACIONAL                        NaN
PCCENTROCUSTO                     ATIVO  VARCHAR2(1)        Indica se o Nível do Centro de custos está ativo.            OPERACIONAL                        NaN
PCCENTROCUSTO         CODIGOCENTROCUSTO VARCHAR2(40)                                Código do centro de custo    CHAVE PRIMÁRIA (PK)                        NaN
PCCENTROCUSTO CODIGOCENTROCUSTOINTFOLHA VARCHAR2(40)                                Cód. Centro de Custo - RM            OPERACIONAL                        NaN
PCCENTROCUSTO                DTINCLUSAO         DATE                                         Data de Inclusão            OPERACIONAL                        NaN
PCCENTROCUSTO               DTALTERACAO         DATE                                        Data de Alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*