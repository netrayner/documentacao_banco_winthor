# 📊 Tabela: PCPREENTDATAVALIDADE

### Estrutura de Colunas e Restrições

              Tabela     Coluna Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPREENTDATAVALIDADE   NUMBONUS  NUMBER(6,0)                 Informação referente ao número do bônus.    CHAVE PRIMÁRIA (PK)                        NaN
PCPREENTDATAVALIDADE    CODPROD  NUMBER(6,0)               Informação referente ao código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCPREENTDATAVALIDADE    NUMLOTE VARCHAR2(15)                  Informação referente ao número do lote.    CHAVE PRIMÁRIA (PK)                        NaN
PCPREENTDATAVALIDADE         QT NUMBER(20,6)          Quantidade de entrada produto incluso no bônus.            OPERACIONAL                        NaN
PCPREENTDATAVALIDADE DTVALIDADE         DATE            Data de validade do produto contido no bônus.    CHAVE PRIMÁRIA (PK)                        NaN
PCPREENTDATAVALIDADE   QTAVARIA NUMBER(20,6) Quantidade de entrada avariada produto incluso no bônus.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*