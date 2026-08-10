# 📊 Tabela: PCINT_RELACIONA_DEPOSITO_ESTOQ

### Estrutura de Colunas e Restrições

                        Tabela                   Coluna  Tipo/Tamanho         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCINT_RELACIONA_DEPOSITO_ESTOQ        CODIGODEPOSITOWMS  NUMBER(10,0)         Código deposito WMS    CHAVE PRIMÁRIA (PK)                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ     DESCRICAODEPOSITOWMS VARCHAR2(100)      Descrição deposito WMS            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ           TIPOESTOQUEERP   VARCHAR2(1)            Tipo estoque ERP            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ        CODIGODEPOSITOERP  VARCHAR2(50)         Código Deposito ERP            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ            PADRAOENTRADA   VARCHAR2(1)              Padrão Entrada            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ              PADRAOSAIDA   VARCHAR2(1)                Padrão Saída            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ   PADRAOCROSSDOCKENTRADA   VARCHAR2(1)    Padrão Crossdock entrada            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ     PADRAOCROSSDOCKSAIDA   VARCHAR2(1)      Padrão Crossdock Saída            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ        PADRAOAVARIASAIDA   VARCHAR2(1)         Padrão Avaria Saída            OPERACIONAL                        NaN
PCINT_RELACIONA_DEPOSITO_ESTOQ PADRAOENTRADADEVOLAVARIA   VARCHAR2(1) Padrão Entrada Devol Avaria            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*