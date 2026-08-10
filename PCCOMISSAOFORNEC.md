# 📊 Tabela: PCCOMISSAOFORNEC

### Estrutura de Colunas e Restrições

          Tabela      Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOFORNEC    CODFAIXA  NUMBER(8,0)    Código da Faixa de Comissionamento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOFORNEC        TIPO  VARCHAR2(3) Indica o tipo da comissão por Cliente            OPERACIONAL                        NaN
PCCOMISSAOFORNEC PERCDESCINI NUMBER(18,6)             Faixa de Desconto Inicial            OPERACIONAL                        NaN
PCCOMISSAOFORNEC PERCDESCFIM NUMBER(18,6)               Faixa de Desconto Final            OPERACIONAL                        NaN
PCCOMISSAOFORNEC      PERCOM  NUMBER(8,4)                Percentual de Comissão            OPERACIONAL                        NaN
PCCOMISSAOFORNEC   CODFORNEC  NUMBER(6,0)                  Código do Fornecedor            OPERACIONAL                        NaN
PCCOMISSAOFORNEC    CODGRUPO  NUMBER(6,0)                       Código do Grupo            OPERACIONAL                        NaN
PCCOMISSAOFORNEC     CODPROD  NUMBER(6,0)                     Código do Produto            OPERACIONAL                        NaN
PCCOMISSAOFORNEC        DATA         DATE                      Data da Inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*