# 📊 Tabela: PCCONTRATOCAMBIO

### Estrutura de Colunas e Restrições

          Tabela             Coluna  Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOCAMBIO        NUMCONTRATO  VARCHAR2(20)                      Número do contrato de câmbio    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCAMBIO         DTCONTRATO          DATE                        Data do contrato de câmbio            OPERACIONAL                        NaN
PCCONTRATOCAMBIO       TIPOCONTRATO   NUMBER(3,0)                                  Tipo do contrato            OPERACIONAL                        NaN
PCCONTRATOCAMBIO           CODBANCO  NUMBER(10,0)                                   Código do banco    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCAMBIO       CODCORRETORA   NUMBER(6,0)                     Código da corretora de cãmbio            OPERACIONAL                        NaN
PCCONTRATOCAMBIO   MOEDAESTRANGEIRA   NUMBER(6,0)                       Código da moeda estrangeira            OPERACIONAL                        NaN
PCCONTRATOCAMBIO           TXCAMBIO  NUMBER(18,6)                                    Taxa de câmbio            OPERACIONAL                        NaN
PCCONTRATOCAMBIO   DTPREVLIQUIDACAO          DATE                     Data prevista para liquidação            OPERACIONAL                        NaN
PCCONTRATOCAMBIO         OBSERVACAO VARCHAR2(200)                                       Observações            OPERACIONAL                        NaN
PCCONTRATOCAMBIO             DTCANC          DATE        Data de cancelamento do contrato de câmbio            OPERACIONAL                        NaN
PCCONTRATOCAMBIO              IBANC  VARCHAR2(20)    Código iBanc da banco destinado para deposito.            OPERACIONAL                        NaN
PCCONTRATOCAMBIO          CODFORNEC   NUMBER(6,0) Código do fornecedor que vai receber o pagamento.            OPERACIONAL                        NaN
PCCONTRATOCAMBIO              PRACA  VARCHAR2(20)                            Identificação da praça            OPERACIONAL                        NaN
PCCONTRATOCAMBIO IDCONTROLEEMBARQUE  VARCHAR2(20)             Identificação no Controle de Embarque            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*