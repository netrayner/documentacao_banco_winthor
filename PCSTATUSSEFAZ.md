# 📊 Tabela: PCSTATUSSEFAZ

### Estrutura de Colunas e Restrições

       Tabela              Coluna  Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSTATUSSEFAZ             SIGLAUF   VARCHAR2(5)                                       Sigla UF da filial            OPERACIONAL                        NaN
PCSTATUSSEFAZ         TIPOSERVICO   VARCHAR2(7) Tipo do serviço (NFE, NFCE, MDFE, CTE, CCE_NFE, CCE_CTE)            OPERACIONAL                        NaN
PCSTATUSSEFAZ            AMBIENTE   VARCHAR2(1)         Tipo do ambiente (homologação = H, produção = P)            OPERACIONAL                        NaN
PCSTATUSSEFAZ              STATUS   VARCHAR2(3)                          Status da consulta, 135 = ativo            OPERACIONAL                        NaN
PCSTATUSSEFAZ     DESCRICAOSTATUS VARCHAR2(120)                                      Descrição do status            OPERACIONAL                        NaN
PCSTATUSSEFAZ     TEMPORESPOSTAMS  NUMBER(18,8)                        Tempo de resposta em milisegundos            OPERACIONAL                        NaN
PCSTATUSSEFAZ DATAHORAULTCONSULTA          DATE                           Data e hora da ultima consulta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*