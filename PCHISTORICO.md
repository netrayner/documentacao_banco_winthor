# 📊 Tabela: PCHISTORICO

### Estrutura de Colunas e Restrições

     Tabela             Coluna Tipo/Tamanho                                                                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCHISTORICO       CODHISTORICO  NUMBER(4,0)                                                                                Indica o código do histórico.    CHAVE PRIMÁRIA (PK)                        NaN
PCHISTORICO     NOME_HISTORICO VARCHAR2(80)                                                                                                          NaN            OPERACIONAL                        NaN
PCHISTORICO PERMITIR_INFOCOMPL      CHAR(1)                                                                                                          NaN            OPERACIONAL                        NaN
PCHISTORICO   COMPOE_DMPL_DLPA  VARCHAR2(1)                 Opção no cadastro de histórico para que esse histórico seja definido se compõe DMPL ou DLPA.            OPERACIONAL                        NaN
PCHISTORICO     LOTEIMPORTACAO NUMBER(10,0) Campo usando para rastrear um lote de importação feito pela rotina 2127, este valor vem da DFSEQ_IMPCONTABIL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*