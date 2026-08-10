# 📊 Tabela: PCCOMISSAOATIVI

### Estrutura de Colunas e Restrições

         Tabela      Coluna Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCOMISSAOATIVI    CODFAIXA  NUMBER(8,0)    Código da Faixa de Comissionamento    CHAVE PRIMÁRIA (PK)                        NaN
PCCOMISSAOATIVI        TIPO  VARCHAR2(3) Indica o tipo da comissão por Cliente            OPERACIONAL                        NaN
PCCOMISSAOATIVI PERCDESCINI NUMBER(18,6)             Faixa de Desconto Inicial            OPERACIONAL                        NaN
PCCOMISSAOATIVI PERCDESCFIM NUMBER(18,6)               Faixa de Desconto Final            OPERACIONAL                        NaN
PCCOMISSAOATIVI      PERCOM  NUMBER(8,4)                Percentual de Comissão            OPERACIONAL                        NaN
PCCOMISSAOATIVI     CODATIV  NUMBER(6,0)                   Código da Atividade            OPERACIONAL                        NaN
PCCOMISSAOATIVI   CODFORNEC  NUMBER(6,0)                  Código do Fornecedor            OPERACIONAL                        NaN
PCCOMISSAOATIVI    CODGRUPO  NUMBER(6,0)                       Código do Grupo            OPERACIONAL                        NaN
PCCOMISSAOATIVI     CODPROD  NUMBER(6,0)                     Código do Produto            OPERACIONAL                        NaN
PCCOMISSAOATIVI        DATA         DATE                      Data da Inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*