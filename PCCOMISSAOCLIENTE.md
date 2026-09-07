# 📊 Tabela: PCCOMISSAOCLIENTE

### Estrutura de Colunas e Restrições

           Tabela      Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOCLIENTE    CODFAIXA  NUMBER(8,0)    Código da Faixa de Comissionamento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOCLIENTE        TIPO  VARCHAR2(3) Indica o tipo da comissão por Cliente            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE PERCDESCINI NUMBER(18,6)             Faixa de Desconto Inicial            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE PERCDESCFIM NUMBER(18,6)               Faixa de Desconto Final            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE      PERCOM  NUMBER(8,4)                Percentual de Comissão            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE      CODCLI  NUMBER(6,0)                     Código do Cliente            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE   CODFORNEC  NUMBER(6,0)                  Código do Fornecedor            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE    CODGRUPO  NUMBER(6,0)                       Código do Grupo            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE     CODPROD  NUMBER(6,0)                     Código do Produto            OPERACIONAL                        NaN
PCCOMISSAOCLIENTE        DATA         DATE                      Data da Inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*