# 📊 Tabela: PCNFCUSTO_JSON

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFCUSTO_JSON         GUID VARCHAR2(37)                              Identificador único do registro da movimentacao            OPERACIONAL                        NaN
PCNFCUSTO_JSON         JSON         CLOB JSON contento todos as variaveis, parametros e valores para calculo do custo            OPERACIONAL                        NaN
PCNFCUSTO_JSON DETALHAMENTO         CLOB                                    Detalhamento completo do calculo do custo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*