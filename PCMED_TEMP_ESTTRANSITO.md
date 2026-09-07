# 📊 Tabela: PCMED_TEMP_ESTTRANSITO

### Estrutura de Colunas e Restrições

                Tabela       Coluna Tipo/Tamanho      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_TEMP_ESTTRANSITO  CODFILIAL_O  VARCHAR2(2)  Código da Filial Origem            OPERACIONAL                        NaN
PCMED_TEMP_ESTTRANSITO    CODPROD_O  NUMBER(6,0) Código do Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_ESTTRANSITO QTTRANSITO_O NUMBER(22,6)  Estoque Trânsito Origem            OPERACIONAL                        NaN
PCMED_TEMP_ESTTRANSITO  CODFILIAL_D  VARCHAR2(2) Código da Filial Destino            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*