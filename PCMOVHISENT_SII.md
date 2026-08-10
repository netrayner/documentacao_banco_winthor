# 📊 Tabela: PCMOVHISENT_SII

### Estrutura de Colunas e Restrições

         Tabela        Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMOVHISENT_SII     CODFILIAL  VARCHAR2(2)               Código Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVHISENT_SII   NUMTRANSENT NUMBER(10,0)           Num.Trans.Entrada.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVHISENT_SII       CODPROD  NUMBER(6,0)              Código Produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVHISENT_SII       DTSAIDA         DATE                        Data.    CHAVE PRIMÁRIA (PK)                        NaN
PCMOVHISENT_SII        QTCONT NUMBER(20,6)                  Qt.Entrada.            OPERACIONAL                        NaN
PCMOVHISENT_SII         SALDO NUMBER(20,6)               Saldo Entrada.            OPERACIONAL                        NaN
PCMOVHISENT_SII NUMTRANSVENDA NUMBER(10,0) NUMERO DE TRANSAÇÃO DE VENDA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*