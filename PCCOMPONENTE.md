# 📊 Tabela: PCCOMPONENTE

### Estrutura de Colunas e Restrições

      Tabela      Coluna   Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMPONENTE     CODCOMP    NUMBER(6,0)         Código do componente    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMPONENTE CODPRODBASE    NUMBER(6,0)       Código do produto base            OPERACIONAL                        NaN
PCCOMPONENTE CODPRODCOMP   VARCHAR2(20) Código do produto componente            OPERACIONAL                        NaN
PCCOMPONENTE    CADASTRO    VARCHAR2(1)                     Cadastro            OPERACIONAL                        NaN
PCCOMPONENTE   DESCRICAO  VARCHAR2(100)                    Descrição            OPERACIONAL                        NaN
PCCOMPONENTE  OBSERVACAO VARCHAR2(1000)                   Observação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*