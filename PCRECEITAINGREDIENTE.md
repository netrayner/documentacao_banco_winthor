# 📊 Tabela: PCRECEITAINGREDIENTE

### Estrutura de Colunas e Restrições

              Tabela           Coluna Tipo/Tamanho                               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRECEITAINGREDIENTE        CODFILIAL  VARCHAR2(2)                                  Código da filial    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAINGREDIENTE          CODPROD  NUMBER(6,0)                       Código do produto produzido    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAINGREDIENTE  CODMATERIAPRIMA NUMBER(10,0)                Código do produto de materia prima    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAINGREDIENTE     QTNECESSARIA NUMBER(22,6)             Quantidade necessária para a produção            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE    PRCNECESSARIA NUMBER(22,6)    Percentual que a produto representa na receita            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE       VLUNITARIO NUMBER(22,6)                         Valor unitário do produto            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE            ETAPA VARCHAR2(15)       Etapa da produção que o produto e utilizado    CHAVE PRIMÁRIA (PK)                        NaN
PCRECEITAINGREDIENTE    QTFRAGMENTADA NUMBER(22,6)                            Quantidade fragmentada            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE PRODUTOPRINCIPAL  VARCHAR2(1) Valida se o produto e a base principal da receita            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE       DTCADASTRO         DATE                                  Data de cadastro            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE      DTALTERACAO         DATE                                 Data de alteração            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE    CODUSUARIOINC  NUMBER(8,0)                     Código do usuário que incluiu            OPERACIONAL                        NaN
PCRECEITAINGREDIENTE    CODUSUARIOALT  NUMBER(8,0)                     Código do usuário que alterou            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*