# 📊 Tabela: PCHISTORICOCASHBACK

### Estrutura de Colunas e Restrições

             Tabela          Coluna Tipo/Tamanho                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICOCASHBACK     NUMDOCTOPDV NUMBER(11,0)      Numero de identificação de venda do PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACK   CODEMPRESAPDV  NUMBER(3,0) Numero da filial que realizou a venda no PDV Supermercados    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACK  CODCHECKOUTPDV  NUMBER(3,0)   Numero do caixa que realizou a venda no PDV Supermercado    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICOCASHBACK         CODPROD  NUMBER(6,0)                    Codigo do produto que originou cashback CHAVE ESTRANGEIRA (FK)                   PCPRODUT
PCHISTORICOCASHBACK CODFINALIZADORA  NUMBER(4,0)             Codigo da finalizadora que originou o cashback CHAVE ESTRANGEIRA (FK)             PCFINALIZADORA
PCHISTORICOCASHBACK   VALORCASHBACK NUMBER(12,2)                                   Valor gerado do cashback            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*