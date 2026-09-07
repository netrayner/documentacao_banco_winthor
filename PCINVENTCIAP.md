# 📊 Tabela: PCINVENTCIAP

### Estrutura de Colunas e Restrições

      Tabela             Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINVENTCIAP      NUMINVENTARIO NUMBER(10,0)                           Número do inventário    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTCIAP          CODFILIAL  VARCHAR2(2)                               Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTCIAP            CODPROD  NUMBER(6,0)                              Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCINVENTCIAP           QTESTGER NUMBER(18,6)                    Quantidade do estoque atual            OPERACIONAL                        NaN
PCINVENTCIAP         QTCONTAGEM NUMBER(18,6)               Quantidade encontrada do produto            OPERACIONAL                        NaN
PCINVENTCIAP         DTINCLUSAO         DATE                 Data de inclusão do inventário            OPERACIONAL                        NaN
PCINVENTCIAP    CODFUNCINCLUSAO  NUMBER(8,0)     Código do usuário que incluiu o inventário            OPERACIONAL                        NaN
PCINVENTCIAP      DTMODIFICACAO         DATE                            Data de modificação            OPERACIONAL                        NaN
PCINVENTCIAP CODFUNCMODIFICACAO  NUMBER(8,0)                Código do usuário que modificou            OPERACIONAL                        NaN
PCINVENTCIAP        DTAPLICACAO         DATE                              Data da aplicação            OPERACIONAL                        NaN
PCINVENTCIAP   CODFUNCAPLICACAO  NUMBER(8,0) Código do funcionário que aplicou o inventário            OPERACIONAL                        NaN
PCINVENTCIAP        NUMTRANSENT NUMBER(10,0)          Número de transação de entrada gerado            OPERACIONAL                        NaN
PCINVENTCIAP      NUMTRANSVENDA NUMBER(10,0)            Número de transação de saída gerado            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*