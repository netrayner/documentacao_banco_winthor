# 📊 Tabela: PCENTREGA

### Estrutura de Colunas e Restrições

   Tabela             Coluna Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCENTREGA          CODENDENT  NUMBER(6,0) Código Endereço de Entrega.    CHAVE PRIMÁRIA (PK)                        NaN
PCENTREGA           CODPRACA  NUMBER(4,0)               Código praça.            OPERACIONAL                        NaN
PCENTREGA             CODCLI  NUMBER(6,0)             Código cliente.            OPERACIONAL                        NaN
PCENTREGA       LOCALENTREGA VARCHAR2(60)              Local entrega.            OPERACIONAL                        NaN
PCENTREGA         ENDENTREGA VARCHAR2(60)           Endereço entrega.            OPERACIONAL                        NaN
PCENTREGA      BAIRROENTREGA VARCHAR2(40)             Bairro entrega.            OPERACIONAL                        NaN
PCENTREGA        MUNIENTREGA VARCHAR2(20)             Cidade entrega.            OPERACIONAL                        NaN
PCENTREGA         ESTENTREGA  VARCHAR2(2)             Estado entrega.            OPERACIONAL                        NaN
PCENTREGA      NUMEROENTREGA  VARCHAR2(6)           Número da Entrega            OPERACIONAL                        NaN
PCENTREGA COMPLEMENTOENTREGA VARCHAR2(80)         Complemento Entrega            OPERACIONAL                        NaN
PCENTREGA         CEPENTREGA  VARCHAR2(9)  CEP do Endereço de Entrega            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*