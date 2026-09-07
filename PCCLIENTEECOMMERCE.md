# 📊 Tabela: PCCLIENTEECOMMERCE

### Estrutura de Colunas e Restrições

            Tabela             Coluna  Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCLIENTEECOMMERCE                 ID  NUMBER(10,0)    Identificador de registro    CHAVE PRIMÁRIA (PK)                        NaN
PCCLIENTEECOMMERCE     CODIGOCOMMERCE  NUMBER(10,0)         Código do ecommerce            OPERACIONAL                        NaN
PCCLIENTEECOMMERCE CLIENTEMARKETPLACE   NUMBER(1,0)          Cliente marketplace            OPERACIONAL                        NaN
PCCLIENTEECOMMERCE        MARKETPLACE VARCHAR2(100)   Descrição do marketplace            OPERACIONAL                        NaN
PCCLIENTEECOMMERCE              EMAIL VARCHAR2(100)             Email do cliente            OPERACIONAL                        NaN
PCCLIENTEECOMMERCE      CODIGOCLIENTE   NUMBER(6,0)   Código do cliente Winthor CHAVE ESTRANGEIRA (FK)                   PCCLIENT
PCCLIENTEECOMMERCE          CODFILIAL   VARCHAR2(2) Código da filial no Winthor CHAVE ESTRANGEIRA (FK)                   PCFILIAL

---
*Documentação gerada automaticamente.*