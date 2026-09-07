# 📊 Tabela: PCRECALCULOPROD

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho                              Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECALCULOPROD     CODFILIAL  VARCHAR2(2)                  Código da filial para recalculo    CHAVE PRIMÁRIA (PK)                        NaN
PCRECALCULOPROD       CODPROD  NUMBER(6,0)              Código do produto a ser recalculado    CHAVE PRIMÁRIA (PK)                        NaN
PCRECALCULOPROD   DTRECALCULO         DATE            Data incial para recalculo do produto            OPERACIONAL                        NaN
PCRECALCULOPROD    DTINCLUSAO         DATE    Data em que o registro foi incluido na tabela            OPERACIONAL                        NaN
PCRECALCULOPROD NUMTRANSVENDA NUMBER(10,0)                                    Numtransvenda    CHAVE PRIMÁRIA (PK)                        NaN
PCRECALCULOPROD            QT NUMBER(20,6)                              Quantidade de itens            OPERACIONAL                        NaN
PCRECALCULOPROD  TIPOREGISTRO  VARCHAR2(1)                        Tipo de registro de venda    CHAVE PRIMÁRIA (PK)                        NaN
PCRECALCULOPROD ATUALIZADO507  VARCHAR2(1) Indica se o registro já foi recalculado pela 507            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*