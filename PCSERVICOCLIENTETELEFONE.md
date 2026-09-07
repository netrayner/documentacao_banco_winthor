# 📊 Tabela: PCSERVICOCLIENTETELEFONE

### Estrutura de Colunas e Restrições

                  Tabela      Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTETELEFONE       FONTE VARCHAR2(255)      Fonte de origem deste telefone            OPERACIONAL                        NaN
PCSERVICOCLIENTETELEFONE      NUMERO  VARCHAR2(50)                  Número de telefone            OPERACIONAL                        NaN
PCSERVICOCLIENTETELEFONE  CODCLIENTE  NUMBER(10,0)     Codigo identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTETELEFONE CODTELEFONE  NUMBER(10,0) Código de identificação do endereço    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*