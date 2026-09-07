# 📊 Tabela: PCPEDCTPIFV

### Estrutura de Colunas e Restrições

     Tabela          Coluna   Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPEDCTPIFV       IMPORTADO    NUMBER(1,0) 1 - Não importado, 2 - Importado com sucesso, 3 - Rejeição            OPERACIONAL                        NaN
PCPEDCTPIFV          NUMPED   NUMBER(10,0)                                           Número do pedido    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCTPIFV     JSON_QRCODE           BLOB                                             JSON do qrCode            OPERACIONAL                        NaN
PCPEDCTPIFV     JSON_STATUS           BLOB                                             JSON do Status            OPERACIONAL                        NaN
PCPEDCTPIFV      DTINCLUSAO           DATE                                           Data da inclusão    CHAVE PRIMÁRIA (PK)                        NaN
PCPEDCTPIFV DTPROCESSAMENTO           DATE                                      Data de processamento            OPERACIONAL                        NaN
PCPEDCTPIFV   OBSERVACAO_PC VARCHAR2(4000)  Armazenará o status de importação ou o motivo de rejeição            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*