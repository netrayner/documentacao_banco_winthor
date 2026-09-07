# 📊 Tabela: PCALCADASAPROVPAGI

### Estrutura de Colunas e Restrições

            Tabela            Coluna Tipo/Tamanho                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALCADASAPROVPAGI         CODFILIAL  VARCHAR2(2)                                                    Código da filial do item da alçada diaria    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADASAPROVPAGI         CODALCADA NUMBER(10,0)                                        Código identificador da alçada a qual pertence o item    CHAVE PRIMÁRIA (PK)         PCALCADASAPROVPAGC
PCALCADASAPROVPAGI     CODALCADAITEM NUMBER(10,0)                                                       Código identificador do item da alçada    CHAVE PRIMÁRIA (PK)                        NaN
PCALCADASAPROVPAGI       CODPARCEIRO NUMBER(10,0)                                            Código do parceiro pra qual foi definida a alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGI           CODFUNC NUMBER(10,0)                                   Código do usuário pra qual será destinado o item da alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGI       DTALCADADIA         DATE                                                      Data do item da alçada referente ao dia            OPERACIONAL                        NaN
PCALCADASAPROVPAGI      VLLIMITELANC NUMBER(16,4) Valor limite permitido por lançamento (valor máximo do título a pagar permitido a autorizar)            OPERACIONAL                        NaN
PCALCADASAPROVPAGI VLLIMITELANCTOTAL NUMBER(16,4)                    Valor limite acumulado total de lançamento permitidos a serem autorizados            OPERACIONAL                        NaN
PCALCADASAPROVPAGI        CODFUNCCAD NUMBER(10,0)                                              Código usuário que cadastrou os itens da alçada            OPERACIONAL                        NaN
PCALCADASAPROVPAGI             DTCAD         DATE                                                  Data em que o item da alçada foi cadastrado            OPERACIONAL                        NaN
PCALCADASAPROVPAGI     CODFUNCULTALT NUMBER(10,0)                   Código do usuário que alterou os dados dos itens da alçada pela última vez            OPERACIONAL                        NaN
PCALCADASAPROVPAGI          DTULTALT         DATE                                              Data em que o item foi alterado pela ultima vez            OPERACIONAL                        NaN
PCALCADASAPROVPAGI      TIPOPARCEIRO  VARCHAR2(1)            Tipo do parceiro pra qual será permitido autorizar pagamento (F, R, C, O ou Nulo)            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*