# 📊 Tabela: PCBENSGRUPO

### Estrutura de Colunas e Restrições

     Tabela                        Coluna  Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBENSGRUPO                      CODGRUPO   NUMBER(6,0)                   Indica o código do grupo de bens.    CHAVE PRIMÁRIA (PK)                        NaN
PCBENSGRUPO                     DESCGRUPO  VARCHAR2(60)                Indica a descrição do grupo de bens.            OPERACIONAL                        NaN
PCBENSGRUPO                 CODPLANOCONTA   NUMBER(5,0)                 Indica o código do plano de contas.            OPERACIONAL                        NaN
PCBENSGRUPO               TAXADEPRECIACAO  NUMBER(10,2)                       Indica a taxa de depreciação.            OPERACIONAL                        NaN
PCBENSGRUPO                    CONTAATIVO  VARCHAR2(60)                            Indica a conta do ativo.            OPERACIONAL                        NaN
PCBENSGRUPO              CONTADEPRECIACAO  VARCHAR2(12)                      Indica a conta de depreciação.            OPERACIONAL                        NaN
PCBENSGRUPO          CONTADESPDEPRECIACAO  VARCHAR2(12)                 Indica a conta despesa depreciação.            OPERACIONAL                        NaN
PCBENSGRUPO                  CODHISTORICO   NUMBER(4,0)                       Indica o código do historico.            OPERACIONAL                        NaN
PCBENSGRUPO           CONTAATIVOCORRIGIDO  VARCHAR2(12)               Conta do ativo para o valor corrigido            OPERACIONAL                        NaN
PCBENSGRUPO     CONTADEPRECIACAOCORRIGIDO  VARCHAR2(12)           Conta depereciação para o valor corrigido            OPERACIONAL                        NaN
PCBENSGRUPO CONTADESPDEPRECIACAOCORRIGIDO  VARCHAR2(12) Conta despesa de depreciação para o valor corrigido            OPERACIONAL                        NaN
PCBENSGRUPO         CODHISTORICOCORRIGIDO   NUMBER(4,0)          Código do histórico para o valor corrigido            OPERACIONAL                        NaN
PCBENSGRUPO           CONTAATIVOATRIBUIDO  VARCHAR2(12)               Conta do ativo para o valor atribuido            OPERACIONAL                        NaN
PCBENSGRUPO     CONTADEPRECIACAOATRIBUIDO  VARCHAR2(12)            Conta depreciação para o valor atribuido            OPERACIONAL                        NaN
PCBENSGRUPO CONTADESPDEPRECIACAOATRIBUIDO  VARCHAR2(12) Conta despesa de depreciação para o valor atribuido            OPERACIONAL                        NaN
PCBENSGRUPO         CODHISTORICOATRIBUIDO   NUMBER(4,0)          Código do histórico para o valor atribuido            OPERACIONAL                        NaN
PCBENSGRUPO            TIPOCONTABILIZACAO   VARCHAR2(1)                   Tipo de valor para contabilização            OPERACIONAL                        NaN
PCBENSGRUPO         FORMULAVALORCORRIGIDO VARCHAR2(500)                          Formula do valor corrigido            OPERACIONAL                        NaN
PCBENSGRUPO         FORMULAVALORATRIBUIDO VARCHAR2(500)                          Formula do valor atribuido            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*