# 📊 Tabela: PCEMBALAGEMVIRTUAL

### Estrutura de Colunas e Restrições

            Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEMBALAGEMVIRTUAL       CODFILIAL  VARCHAR2(4)                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEMVIRTUAL         CODPROD NUMBER(18,0)                 Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEMVIRTUAL     CODAUXILIAR NUMBER(18,0)                  Código de barras    CHAVE PRIMÁRIA (PK)                        NaN
PCEMBALAGEMVIRTUAL          QTUNIT NUMBER(18,6) Quantidade unitária por embalagem            OPERACIONAL                        NaN
PCEMBALAGEMVIRTUAL QTMINIMAATACADO NUMBER(18,6)                Gatilho de atacado            OPERACIONAL                        NaN
PCEMBALAGEMVIRTUAL       DTALTERC5 TIMESTAMP(6)                 Data de alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*