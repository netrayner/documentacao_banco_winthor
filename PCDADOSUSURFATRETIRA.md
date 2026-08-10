# 📊 Tabela: PCDADOSUSURFATRETIRA

### Estrutura de Colunas e Restrições

              Tabela               Coluna Tipo/Tamanho                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDADOSUSURFATRETIRA               NUMDOC NUMBER(10,0)                        Número do Documento    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSUSURFATRETIRA              TIPODOC  VARCHAR2(1)                          Tipo do Documento    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSUSURFATRETIRA         CODIGOFILIAL  VARCHAR2(2)                           Código da Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCDADOSUSURFATRETIRA           CODVEICULO NUMBER(10,0)                          Código do Veículo            OPERACIONAL                        NaN
PCDADOSUSURFATRETIRA CODIGOTRANSPORTADORA NUMBER(10,0)                   Código da Transportadora            OPERACIONAL                        NaN
PCDADOSUSURFATRETIRA       CODCONTATRANSF NUMBER(10,0) Código da Conta Gerencial de Transferência            OPERACIONAL                        NaN
PCDADOSUSURFATRETIRA               CODCOB  VARCHAR2(4)    Código de Cobrança Transferência Retira            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*