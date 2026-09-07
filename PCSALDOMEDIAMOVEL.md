# 📊 Tabela: PCSALDOMEDIAMOVEL

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSALDOMEDIAMOVEL    CODFILIAL  VARCHAR2(2)    Código Filial do saldo em questão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOMEDIAMOVEL          ANO  NUMBER(4,0)              Ano do saldo em questão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOMEDIAMOVEL          MES  NUMBER(2,0)              Mês do saldo em questão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOMEDIAMOVEL      CODPROD  NUMBER(6,0)   Código Produto do saldo em questão.    CHAVE PRIMÁRIA (PK)                        NaN
PCSALDOMEDIAMOVEL     QTBASEST NUMBER(20,6)           Qtde em estoque do produto.            OPERACIONAL                        NaN
PCSALDOMEDIAMOVEL VLUNITBASEST NUMBER(16,4) Valor unitário da base ST do produto.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*