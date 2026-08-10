# 📊 Tabela: PCREINFR4020C

### Estrutura de Colunas e Restrições

       Tabela       Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR4020C           ID   NUMBER(8,0)                     Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR4020C      GRUPOID   NUMBER(8,0)            Identificador do grupo            OPERACIONAL                        NaN
PCREINFR4020C          MES   NUMBER(8,0)                 Mês de referência            OPERACIONAL                        NaN
PCREINFR4020C          ANO   NUMBER(8,0)                 Ano de referência            OPERACIONAL                        NaN
PCREINFR4020C    CODFORNEC   NUMBER(8,0)              Código do fornecedor            OPERACIONAL                        NaN
PCREINFR4020C TIPOPARCEIRO   VARCHAR2(1)                  Tipo do parceiro            OPERACIONAL                        NaN
PCREINFR4020C    CODFILIAL   VARCHAR2(2)                  Código da filial            OPERACIONAL                        NaN
PCREINFR4020C       RECIBO VARCHAR2(150) Numero de identificação do recibo            OPERACIONAL                        NaN
PCREINFR4020C       ID_XML VARCHAR2(100)                Id do XML de envio            OPERACIONAL                        NaN
PCREINFR4020C  DTALTERACAO          DATE                 Data da alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*