# 📊 Tabela: PCINUTILIZACAONFCE

### Estrutura de Colunas e Restrições

            Tabela                Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINUTILIZACAONFCE             CODFILIAL   VARCHAR2(6)                             Código Filial    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAONFCE   DTHORAPROCESSAMENTO          DATE                     Data do processamento            OPERACIONAL                        NaN
PCINUTILIZACAONFCE         JUSTIFICATIVA VARCHAR2(256)             Justificativa da inutilização            OPERACIONAL                        NaN
PCINUTILIZACAONFCE        NUMNOTAINICIAL  NUMBER(10,0)                        Nº da nota Inicial    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAONFCE          NUMNOTAFINAL  NUMBER(10,0)                          Nº da Nota final    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAONFCE                   ANO   NUMBER(6,0)                                       Ano    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAONFCE            CODUSUARIO   NUMBER(8,0)                         Código do usuário            OPERACIONAL                        NaN
PCINUTILIZACAONFCE PROTOCOLOINUTILIZACAO  VARCHAR2(20)           Nº do protocolo da inutiilzação            OPERACIONAL                        NaN
PCINUTILIZACAONFCE              AMBIENTE   VARCHAR2(1)         Ambiente do envio da inutilização            OPERACIONAL                        NaN
PCINUTILIZACAONFCE                  DATA          DATE                Data da inutilizacao NFCe.            OPERACIONAL                        NaN
PCINUTILIZACAONFCE              NUMCAIXA   NUMBER(4,0)                           numero do caixa            OPERACIONAL                        NaN
PCINUTILIZACAONFCE                 SERIE   VARCHAR2(6)                Série vinculada a um caixa    CHAVE PRIMÁRIA (PK)                        NaN
PCINUTILIZACAONFCE             EXPORTADO   VARCHAR2(1) Indica se o registro foi exportado (S/N).            OPERACIONAL                        NaN
PCINUTILIZACAONFCE               POSICAO   VARCHAR2(1)           Posição/status da inutilização.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*