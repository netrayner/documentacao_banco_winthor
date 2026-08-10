# 📊 Tabela: PCLOTEPREENT

### Estrutura de Colunas e Restrições

      Tabela      Coluna Tipo/Tamanho                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOTEPREENT NUMTRANSENT NUMBER(10,0)                           Campo para armazenar número da transação da pré-entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCLOTEPREENT     CODPROD  NUMBER(6,0)   Campo para armazenar código do produto que possua lote informado na pré-entrada.            OPERACIONAL                        NaN
PCLOTEPREENT     NUMLOTE VARCHAR2(15)     Campo para armazenar o número do lote informado para o produto da pré-entrada.            OPERACIONAL                        NaN
PCLOTEPREENT          QT NUMBER(19,3) Campo para armazenar a quantidade do lote informado para o produto da pré-entrada.            OPERACIONAL                        NaN
PCLOTEPREENT  DTVALIDADE         DATE                   Data de validade do lote informado para o produto da pré-entrada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*