# 📊 Tabela: PCINTEGRARPEDIDOS

### Estrutura de Colunas e Restrições

           Tabela           Coluna Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINTEGRARPEDIDOS      INTEGRADORA  NUMBER(6,0) O código da integração.            OPERACIONAL                        NaN
PCINTEGRARPEDIDOS STATUSINTEGRACAO VARCHAR2(30)      O status do pedido            OPERACIONAL                        NaN
PCINTEGRARPEDIDOS    CODREFERENCIA VARCHAR2(10) O código da referência.            OPERACIONAL                        NaN
PCINTEGRARPEDIDOS           NUMPED NUMBER(10,0)        Número do Pedido    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*