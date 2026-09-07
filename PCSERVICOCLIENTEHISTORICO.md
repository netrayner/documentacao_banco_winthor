# 📊 Tabela: PCSERVICOCLIENTEHISTORICO

### Estrutura de Colunas e Restrições

                   Tabela            Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERVICOCLIENTEHISTORICO   DATAMODIFICACAO          DATE        Data que a modificação ocorreu            OPERACIONAL                        NaN
PCSERVICOCLIENTEHISTORICO     USUARIOLOGADO VARCHAR2(255)        Email do usuário que modificou            OPERACIONAL                        NaN
PCSERVICOCLIENTEHISTORICO RESULTADOOPERACAO  VARCHAR2(50) Resultado da operação: SUCESSO, FALHA            OPERACIONAL                        NaN
PCSERVICOCLIENTEHISTORICO         DESCRICAO VARCHAR2(255)                 Descrição da operação            OPERACIONAL                        NaN
PCSERVICOCLIENTEHISTORICO      TIPOOPERACAO VARCHAR2(255)                      Tipo da operação            OPERACIONAL                        NaN
PCSERVICOCLIENTEHISTORICO        CODCLIENTE  NUMBER(10,0)       Código identificador do cliente CHAVE ESTRANGEIRA (FK)           PCSERVICOCLIENTE
PCSERVICOCLIENTEHISTORICO      CODHISTORICO  NUMBER(10,0)     Código identificador do histórico    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*