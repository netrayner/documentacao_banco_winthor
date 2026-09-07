# 📊 Tabela: PCESTOQUETERCEIRO

### Estrutura de Colunas e Restrições

           Tabela           Coluna Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCESTOQUETERCEIRO        CODFILIAL  VARCHAR2(2)                                   Código da filial de origem da venda TV-10.            OPERACIONAL                        NaN
PCESTOQUETERCEIRO      CODDEPOSITO NUMBER(10,0)                       Código de depósito na filial de origem da venda TV-10.            OPERACIONAL                        NaN
PCESTOQUETERCEIRO          CODPROD  NUMBER(6,0)                                               Código do produto em trânsito.            OPERACIONAL                        NaN
PCESTOQUETERCEIRO       QUANTIDADE NUMBER(20,6)                                           Quantidade do produto em trânsito.            OPERACIONAL                        NaN
PCESTOQUETERCEIRO CODFILIALDESTINO  VARCHAR2(2)                                  Código da filial de destino da venda TV-10.            OPERACIONAL                        NaN
PCESTOQUETERCEIRO      CNPJDESTINO VARCHAR2(14) Informa o CNPJ relacionado ao CODFILIAL da filial de destino da venda TV-10.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*