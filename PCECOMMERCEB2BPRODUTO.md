# 📊 Tabela: PCECOMMERCEB2BPRODUTO

### Estrutura de Colunas e Restrições

               Tabela         Coluna Tipo/Tamanho                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCECOMMERCEB2BPRODUTO      CODFILIAL  VARCHAR2(2)                                                      Código da filial da integração B2B    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPRODUTO TIPOINTEGRACAO  NUMBER(4,0)                                                               Tipo de integração do B2B    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPRODUTO        CODPROD  NUMBER(6,0)                                                                       Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPRODUTO    CODAUXILIAR VARCHAR2(18) Código de barras formatado com código EAN e fator de conversão, separados pela letra C.            OPERACIONAL                        NaN
PCECOMMERCEB2BPRODUTO  TIPOCONVERSAO VARCHAR2(20)                             Tipo de conversão (UNIDADE, MASTER, EMBALAGEM ou ALIENACAO)    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPRODUTO FATORCONVERSAO NUMBER(18,6)                                   Fator de conversão para o envio de estoque para o B2B    CHAVE PRIMÁRIA (PK)                        NaN
PCECOMMERCEB2BPRODUTO     DTINCLUSAO         DATE                                                           Data de inclusão do registro.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*