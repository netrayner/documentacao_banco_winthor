# 📊 Tabela: PCMOVSERIE

### Estrutura de Colunas e Restrições

    Tabela        Coluna Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVSERIE NUMTRANSVENDA NUMBER(10,0)                               Indica o numero da transação realizada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSERIE       CODPROD  NUMBER(6,0)                                           Indica o código do Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSERIE        NUMSEQ NUMBER(20,0)                       Indica o número de Sequencia dos itens da nota.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSERIE      NUMSERIE VARCHAR2(20)                            Indica o número de série a ser cadastrado.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVSERIE  DATACADASTRO         DATE                      Indica a data de cadastro da série dos produtos.            OPERACIONAL                        NaN
PCMOVSERIE       USUARIO  NUMBER(8,0) Indica o usuário que está realizando a inclusão dos números de série.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*