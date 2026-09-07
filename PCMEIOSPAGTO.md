# 📊 Tabela: PCMEIOSPAGTO

### Estrutura de Colunas e Restrições

      Tabela         Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMEIOSPAGTO      CODFILIAL  VARCHAR2(2) Código da filial do meio de pagamento.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO       NUMCAIXA  NUMBER(4,0)                       Número do caixa.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO NUMCAIXAFISCAL  NUMBER(4,0)     Número do emissor de cupom fiscal.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO         CODCOB  VARCHAR2(4)                    Código de cobrança.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO           DATA         DATE                        Data da compra.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO        TIPODOC VARCHAR2(30)                     Tipo de documento.    CHAVE PRIMÁRIA (PK)                        NaN
PCMEIOSPAGTO          VALOR NUMBER(12,2)           Valor da forma de pagamento.            OPERACIONAL                        NaN
PCMEIOSPAGTO       EXPORTOU  VARCHAR2(1)                             Exportado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*