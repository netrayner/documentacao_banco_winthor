# 📊 Tabela: PCCONTRATOCOMODLOCI

### Estrutura de Colunas e Restrições

             Tabela         Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTRATOCOMODLOCI    NUMCONTRATO  NUMBER(8,0)          Indica o número do contrato.    CHAVE PRIMÁRIA (PK)         PCCONTRATOCOMODLOC
PCCONTRATOCOMODLOCI        CODPROD  NUMBER(6,0)           Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCOMODLOCI      VLLOCACAO NUMBER(10,2) Indica o valor de locação do produto.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOCI  NUMTRANSVENDA NUMBER(10,0)          Indica a transação de venda.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCOMODLOCI    NUMTRANSENT NUMBER(10,0)        Indica a transação de entrada.            OPERACIONAL                        NaN
PCCONTRATOCOMODLOCI CODEQUIPAMENTO NUMBER(10,0)     Código do equipamento comodatado.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTRATOCOMODLOCI    DTDEVOLUCAO         DATE            Data de devolução do item.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*