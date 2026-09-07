# 📊 Tabela: PCLFPISREG0110

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFPISREG0110   CODFILIAL  VARCHAR2(2)                                             Código da Filial.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0110     DATAINI         DATE                          Data Inicial do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0110     DATAFIM         DATE                            Data Final do Período Selecionado.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFPISREG0110  CODINCTRIB  NUMBER(1,0)         Código indicador da incidência tributária no período.            OPERACIONAL                        NaN
PCLFPISREG0110 CODTIPOCONT  NUMBER(1,0)             Código indicador do Tipo de Contribuição Apurada.            OPERACIONAL                        NaN
PCLFPISREG0110 INDAPROCRED  NUMBER(1,0) Código indicador de método de apropriação de créditos comuns.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*