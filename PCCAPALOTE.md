# 📊 Tabela: PCCAPALOTE

### Estrutura de Colunas e Restrições

    Tabela           Coluna Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCAPALOTE      CODCAPALOTE NUMBER(10,0)   NUMERO SEQUENCIAL CAPA LOTE    CHAVE PRIMÁRIA (PK)                        NaN
PCCAPALOTE      AMBIENTECLE  VARCHAR2(1)         AMBIENTE CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE      SITUACAOCLE NUMBER(10,0)         SITUACAO CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE          NUMVIAS NUMBER(10,0)      NUMERO DE VIAS IMPRESSAS            OPERACIONAL                        NaN
PCCAPALOTE         CHAVECLE VARCHAR2(14)            CHAVE CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE        CODFILIAL  VARCHAR2(2)              CODIGO DA FILIAL            OPERACIONAL                        NaN
PCCAPALOTE MODALIDADETRANSP  VARCHAR2(2)      MODALIDADE DE TRANSPORTE            OPERACIONAL                        NaN
PCCAPALOTE         UFORIGEM  VARCHAR2(2)  UF DE ORIGEM DA CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE        UFDESTINO  VARCHAR2(2) UF DE DESTINO DA CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE          DATACLE         DATE             DATA CAPA DE LOTE            OPERACIONAL                        NaN
PCCAPALOTE     PLACAVEICULO  VARCHAR2(8)              PLACA DO VEICULO            OPERACIONAL                        NaN
PCCAPALOTE   UFPLACAVEICULO  VARCHAR2(2)        UF DA PLACA DO VEICULO            OPERACIONAL                        NaN
PCCAPALOTE    PLACACARRETA1  VARCHAR2(8)            PLACA DA CARRETA 1            OPERACIONAL                        NaN
PCCAPALOTE  UFPLACACARRETA1  VARCHAR2(2)      UF DA PLACA DA CARRETA 1            OPERACIONAL                        NaN
PCCAPALOTE    PLACACARRETA2  VARCHAR2(8)            PLACA DA CARRETA 2            OPERACIONAL                        NaN
PCCAPALOTE  UFPLACACARRETA2  VARCHAR2(2)         UF PLACA DA CARRETA 2            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*