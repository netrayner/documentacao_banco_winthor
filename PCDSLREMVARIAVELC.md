# 📊 Tabela: PCDSLREMVARIAVELC

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDSLREMVARIAVELC   IDAPURACAO  NUMBER(8,0)       Identificação apuração remuneração variável.    CHAVE PRIMÁRIA (PK)                        NaN
PCDSLREMVARIAVELC    CODFILIAL  VARCHAR2(2)                                     Código filial.            OPERACIONAL                        NaN
PCDSLREMVARIAVELC  CODCAMPANHA  NUMBER(8,0)        Código da campanha de remuneração variável.            OPERACIONAL                        NaN
PCDSLREMVARIAVELC  MESAPURACAO  NUMBER(6,0)                             Mês e Ano de apuração.            OPERACIONAL                        NaN
PCDSLREMVARIAVELC CODFUNCFECHA  NUMBER(8,0) Código do funcionário responsável pelo fechamento.            OPERACIONAL                        NaN
PCDSLREMVARIAVELC DTFECHAMENTO         DATE                    Data de fechamento da apuração.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*