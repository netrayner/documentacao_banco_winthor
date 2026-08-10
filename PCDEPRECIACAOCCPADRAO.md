# 📊 Tabela: PCDEPRECIACAOCCPADRAO

### Estrutura de Colunas e Restrições

               Tabela            Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEPRECIACAOCCPADRAO CODIGOCENTROCUSTO VARCHAR2(40)                      Código do Centro de Custos    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAOCCPADRAO     CODPLANOCONTA  NUMBER(5,0)                       Código do Plano de Contas    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAOCCPADRAO    CODREDUZIDO_PC VARCHAR2(12)               Código Reduzido da Conta Contábil    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAOCCPADRAO   TIPODEPRECIACAO  VARCHAR2(1) B-VALOR BEM C-VALOR CORRIGIDO A-VALOR ATRIBUIDO    CHAVE PRIMÁRIA (PK)                        NaN
PCDEPRECIACAOCCPADRAO        PERCENTUAL NUMBER(10,6)                            Percentual de Rateio            OPERACIONAL                        NaN
PCDEPRECIACAOCCPADRAO          CODGRUPO  NUMBER(6,0)                                 Código do Grupo    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*