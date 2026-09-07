# 📊 Tabela: PCPRODCONTROLEVENDA

### Estrutura de Colunas e Restrições

             Tabela                 Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODCONTROLEVENDA                CODPROD  NUMBER(6,0)                       Código do Produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCONTROLEVENDA   CODTIPOCONTROLEVENDA  NUMBER(3,0)     Código do Tipo de Controle de Venda    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODCONTROLEVENDA      QTLIMISENCAOPFMES NUMBER(16,3)   Qt. Limite Isenção Pessoa Fisica Mês.            OPERACIONAL                        NaN
PCPRODCONTROLEVENDA      QTLIMISENCAOPJMES NUMBER(16,3) Qt. Limite Isenção Pessoa Juridica Mês.            OPERACIONAL                        NaN
PCPRODCONTROLEVENDA QTLIMISENCAODISTRIBMES NUMBER(16,3)         Qt. Limite Isenção Distribuidor            OPERACIONAL                        NaN
PCPRODCONTROLEVENDA           QTLIMPESOMES NUMBER(16,3)         Peso limite autorizado por mês.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*