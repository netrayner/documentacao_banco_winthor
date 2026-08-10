# 📊 Tabela: PCFORNECCOTACAO

### Estrutura de Colunas e Restrições

         Tabela     Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORNECCOTACAO  CODFORNEC  NUMBER(6,0)                        Indica o código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCFORNECCOTACAO NUMCOTACAO  NUMBER(8,0)                           Indica o número da cotação.    CHAVE PRIMÁRIA (PK)                  PCCOTACAO
PCFORNECCOTACAO   SITUACAO  VARCHAR2(1)            Situação da cotação A-aberta ou F-fechada.            OPERACIONAL                        NaN
PCFORNECCOTACAO CODPARCELA  NUMBER(6,0) Código de prazo de pagamento cadastro pela rotina 256            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*