# 📊 Tabela: PCDESCONTOAUTOC

### Estrutura de Colunas e Restrições

         Tabela            Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOAUTOC            NUMPED NUMBER(10,0)                         NÚMERO DO PEDIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCDESCONTOAUTOC STATUSAUTORIZACAO  VARCHAR2(1)                       STATUS AUTORIZACAO            OPERACIONAL                        NaN
PCDESCONTOAUTOC     CODFUNCAUTORI  NUMBER(8,0) CÓDIGO DO USUÁRIO QUE AUTORIZOU DESCONTO            OPERACIONAL                        NaN
PCDESCONTOAUTOC           PERDESC NUMBER(18,6)                   PERCENTUAL DE DESCONTO            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*