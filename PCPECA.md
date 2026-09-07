# 📊 Tabela: PCPECA

### Estrutura de Colunas e Restrições

Tabela           Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPECA          CODPECA NUMBER(10,0)                               Código da Peça    CHAVE PRIMÁRIA (PK)                        NaN
PCPECA     REGISTROPECA VARCHAR2(15)                                          NaN            OPERACIONAL                        NaN
PCPECA        DESCRICAO VARCHAR2(40)                            Descrição da Peça            OPERACIONAL                        NaN
PCPECA        CODFORNEC  NUMBER(6,0)                         Código do Fornecedor            OPERACIONAL                        NaN
PCPECA          CODEPTO NUMBER(10,0)                       Código do Departamento            OPERACIONAL                        NaN
PCPECA           CODSEC  NUMBER(6,0)                              Código da Seção            OPERACIONAL                        NaN
PCPECA     CODCATEGORIA  NUMBER(6,0)                          Código da Categoria            OPERACIONAL                        NaN
PCPECA  CODSUBCATEGORIA  NUMBER(6,0)                      Código da Sub-Categoria            OPERACIONAL                        NaN
PCPECA         CODMARCA  NUMBER(8,0)                              Código da Marca            OPERACIONAL                        NaN
PCPECA REGISTROPECANOVO VARCHAR2(15)                                          NaN            OPERACIONAL                        NaN
PCPECA   PRECOORCAMENTO NUMBER(24,6)                   Preço de Orçamento da Peça            OPERACIONAL                        NaN
PCPECA          CODPROD  NUMBER(6,0)                               Código Produto            OPERACIONAL                        NaN
PCPECA           STATUS  VARCHAR2(1) Define se a peça está ativa(A) ou Inativa(I)            OPERACIONAL                        NaN
PCPECA       DTEXCLUSAO         DATE                     Data de Exclusão da Peça            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*