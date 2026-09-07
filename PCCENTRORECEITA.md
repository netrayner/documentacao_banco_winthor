# 📊 Tabela: PCCENTRORECEITA

### Estrutura de Colunas e Restrições

         Tabela                     Coluna Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCENTRORECEITA        CODIGOCENTRORECEITA VARCHAR2(40)                                                            Código do centro de receita.    CHAVE PRIMÁRIA (PK)                        NaN
PCCENTRORECEITA                  DESCRICAO VARCHAR2(40)                                                         Descrição do centro de receita.            OPERACIONAL                        NaN
PCCENTRORECEITA                      ATIVO  VARCHAR2(1)                                      Indica se o nível do centro de receita está ativo.            OPERACIONAL                        NaN
PCCENTRORECEITA              RECEBE_LANCTO  VARCHAR2(1)                              Indica se o nível do centro de receita recebe lançamentos.            OPERACIONAL                        NaN
PCCENTRORECEITA                 DTINCLUSAO         DATE                                                        Data de inclusão (somente data).            OPERACIONAL                        NaN
PCCENTRORECEITA                DTALTERACAO         DATE                                                       Data de alteração (somente data).            OPERACIONAL                        NaN
PCCENTRORECEITA CLASSIFICACAOCENTRORECEITA  VARCHAR2(1) Indica a classificação do centro de receita do parâmetro 4154 da rotina 132 no momento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*