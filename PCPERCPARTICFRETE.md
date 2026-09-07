# 📊 Tabela: PCPERCPARTICFRETE

### Estrutura de Colunas e Restrições

           Tabela       Coluna Tipo/Tamanho                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPERCPARTICFRETE       CODIGO  NUMBER(6,0)                             Código do Registro    CHAVE PRIMÁRIA (PK)                        NaN
PCPERCPARTICFRETE    CODFILIAL  VARCHAR2(2)                               Código da Filial            OPERACIONAL                        NaN
PCPERCPARTICFRETE     VLINICIO NUMBER(18,6)                         Faixa de Valor inicial            OPERACIONAL                        NaN
PCPERCPARTICFRETE      VLFINAL NUMBER(18,6)                           Faixa de Valor Final            OPERACIONAL                        NaN
PCPERCPARTICFRETE PERCPARTICIP NUMBER(18,6) Percentual de participação da empresa no frete            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*