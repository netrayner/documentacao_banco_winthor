# 📊 Tabela: PCGERAICMSLIVROFISCALSAIDA

### Estrutura de Colunas e Restrições

                    Tabela              Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCGERAICMSLIVROFISCALSAIDA             CODPROD  NUMBER(6,0)            CÓDIGO DO PRODUTO    CHAVE PRIMÁRIA (PK)                   PCPRODUT
PCGERAICMSLIVROFISCALSAIDA           CODFILIAL  VARCHAR2(2)             CÓDIGO DA FILIAL    CHAVE PRIMÁRIA (PK)                   PCFILIAL
PCGERAICMSLIVROFISCALSAIDA           CONDVENDA  NUMBER(5,0)        CONDIÇÃO DE PAGAMENTO    CHAVE PRIMÁRIA (PK)                        NaN
PCGERAICMSLIVROFISCALSAIDA GERAICMSLIVROFISCAL  VARCHAR2(1) DEVE GERAR ICMS LIVRO FISCAL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*