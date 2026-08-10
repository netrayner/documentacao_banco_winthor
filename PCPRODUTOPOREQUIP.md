# 📊 Tabela: PCPRODUTOPOREQUIP

### Estrutura de Colunas e Restrições

           Tabela         Coluna Tipo/Tamanho              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTOPOREQUIP   CODPRODEQUIP  NUMBER(6,0)   Código do Produto Equipamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOPOREQUIP CODEQUIPAMENTO NUMBER(10,0)           Codigo do Equipamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOPOREQUIP   IDPATRIMONIO VARCHAR2(75)     Identificação do Patrimonio.            OPERACIONAL                        NaN
PCPRODUTOPOREQUIP        CODPROD  NUMBER(6,0)               Codigo do Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOPOREQUIP         CODCLI  NUMBER(8,0)               Código do Cliente.    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTOPOREQUIP  PERIODICIDADE  NUMBER(4,0)           Periodicidade em dias.            OPERACIONAL                        NaN
PCPRODUTOPOREQUIP             QT NUMBER(20,6)                      Quantidade.            OPERACIONAL                        NaN
PCPRODUTOPOREQUIP         DTLANC         DATE              Data do lançamento.            OPERACIONAL                        NaN
PCPRODUTOPOREQUIP    CODFUNCLANC  NUMBER(8,0)       Funcionário do lançamento.            OPERACIONAL                        NaN
PCPRODUTOPOREQUIP         STATUS  VARCHAR2(1) Situação do produto equipamento.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*