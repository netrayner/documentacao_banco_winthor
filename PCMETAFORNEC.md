# 📊 Tabela: PCMETAFORNEC

### Estrutura de Colunas e Restrições

      Tabela       Coluna Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMETAFORNEC    CODFILIAL  VARCHAR2(2)                Indica o código da filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAFORNEC    CODFORNEC  NUMBER(6,0)            Indica o código do fornecedor.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAFORNEC         DATA         DATE        Indica a data de inclisão da meta.    CHAVE PRIMÁRIA (PK)                        NaN
PCMETAFORNEC PERVENDAPREV  NUMBER(5,2) Indica a previsão do percentual de venda.            OPERACIONAL                        NaN
PCMETAFORNEC  VLVENDAPREV NUMBER(14,2)      Indica a previsão do valor de venda.            OPERACIONAL                        NaN
PCMETAFORNEC      VLVENDA NUMBER(14,2)                Indica a previsão de venda            OPERACIONAL                        NaN
PCMETAFORNEC  VLCUSTOREAL NUMBER(14,2)             Indica o valor do custo real.            OPERACIONAL                        NaN
PCMETAFORNEC   VLCUSTOFIN NUMBER(14,2)       Indica o valor do custo financeiro.            OPERACIONAL                        NaN
PCMETAFORNEC     VLTABELA NUMBER(14,2)                 Indica o valor de tabela.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*