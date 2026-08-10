# 📊 Tabela: PCSERVICOCLIENTESOCIO

### Estrutura de Colunas e Restrições

               Tabela           Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTESOCIO      RAZAOSOCIAL VARCHAR2(255)               Razão social do sócio            OPERACIONAL                        NaN
PCSERVICOCLIENTESOCIO CAPITALINVESTIDO VARCHAR2(255)                   Capital investido            OPERACIONAL                        NaN
PCSERVICOCLIENTESOCIO             CNPJ  VARCHAR2(50)                                CNPJ            OPERACIONAL                        NaN
PCSERVICOCLIENTESOCIO       CODCLIENTE  NUMBER(10,0)     Codigo Identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTESOCIO         CODSOCIO  NUMBER(10,0) Código de identificação do endereço    CHAVE PRIMÁRIA (PK)                        NaN
PCSERVICOCLIENTESOCIO         REGISTRO  VARCHAR2(50)                 Registro do cliente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*