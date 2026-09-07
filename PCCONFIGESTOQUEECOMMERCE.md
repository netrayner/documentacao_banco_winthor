# 📊 Tabela: PCCONFIGESTOQUEECOMMERCE

### Estrutura de Colunas e Restrições

                  Tabela            Coluna Tipo/Tamanho                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFIGESTOQUEECOMMERCE                ID NUMBER(22,0) Identificador gerado automaticamente            OPERACIONAL                        NaN
PCCONFIGESTOQUEECOMMERCE         CODFILIAL  VARCHAR2(2)               ID da filial ecommerce CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCCONFIGESTOQUEECOMMERCE      FAIXAINICIAL NUMBER(18,3)               Faixa de preço inicial            OPERACIONAL                        NaN
PCCONFIGESTOQUEECOMMERCE        FAIXAFINAL NUMBER(18,3)                 Faixa de preço final            OPERACIONAL                        NaN
PCCONFIGESTOQUEECOMMERCE PERCENTUALESTOQUE  NUMBER(6,3)   Percentual de estoque para a faixa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*