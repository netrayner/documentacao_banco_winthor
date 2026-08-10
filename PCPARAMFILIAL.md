# 📊 Tabela: PCPARAMFILIAL

### Estrutura de Colunas e Restrições

       Tabela     Coluna   Tipo/Tamanho                                                                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMFILIAL       NOME   VARCHAR2(34)                                                                                     Nome do parâmetro.    CHAVE PRIMÁRIA (PK)          PCMETAPARAMFILIAL
PCPARAMFILIAL  CODFILIAL    VARCHAR2(2) Código da filial que o parâmetro está relacionado. Use 999 para valores por empresa, e não por filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMFILIAL      VALOR VARCHAR2(1000)           Valor do parâmetros. O valor do parâmetro deve ser convertido para varchar2 antes de salvar.            OPERACIONAL                        NaN
PCPARAMFILIAL DTMXSALTER           DATE                                                                                                    NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*