# 📊 Tabela: PCINUTILIZACAOCTE

### Estrutura de Colunas e Restrições

           Tabela                Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINUTILIZACAOCTE             CODFILIAL   VARCHAR2(2)                  Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAOCTE   DTHORAPROCESSAMENTO          DATE   Indica a data do processamento do pedido.            OPERACIONAL                        NaN
PCINUTILIZACAOCTE         JUSTIFICATIVA VARCHAR2(256)     Indica a justificativa da inutilizacao.            OPERACIONAL                        NaN
PCINUTILIZACAOCTE        NUMNOTAINICIAL  NUMBER(10,0)    Indica o número inicial de inutilização.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAOCTE          NUMNOTAFINAL  NUMBER(10,0)      Indica o número final de inutilização.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAOCTE                 SERIE   NUMBER(5,0)           Indica o série do número da nota.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAOCTE                   ANO   NUMBER(6,0)     Indica o ano do número de inutilização.    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAOCTE            CODUSUARIO   NUMBER(8,0) Indica o código do usuário de inutilização.            OPERACIONAL                        NaN
PCINUTILIZACAOCTE PROTOCOLOINUTILIZACAO  VARCHAR2(20)           Indica protocolo de inutilização.            OPERACIONAL                        NaN
PCINUTILIZACAOCTE              AMBIENTE   VARCHAR2(1)          Indica o ambiente de inutilização.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*