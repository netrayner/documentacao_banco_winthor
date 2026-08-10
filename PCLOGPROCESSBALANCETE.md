# 📊 Tabela: PCLOGPROCESSBALANCETE

### Estrutura de Colunas e Restrições

               Tabela     Coluna  Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGPROCESSBALANCETE    CODFUNC   NUMBER(8,0)                                                                Código do usuario do Winthor que emitiu o relatorio.            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE     OSUSER  VARCHAR2(30)                                                       Nome de usuario do sistema operacional que emitiu o relatorio            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE    MAQUINA  VARCHAR2(64)                                       Nome da maquina atribuida ao sistema operacional onde foi emitido o relatorio            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE  CODROTINA   NUMBER(6,0)                                                                 Código da rotina pela qual foi emitido o relatorio.            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE     CONTAS          BLOB                                                                                   Nome do relatorio que foi emitido            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE    NOMEREL  VARCHAR2(60) Contas que estavam restritas no momento da emissao do relatorio contendo formato de grupo:conta, separados por ','             OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE   DATAHORA          DATE                                                                         Data e hora a qual foi emitido o relatorio.            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE OBSERVACAO VARCHAR2(300)                        Observações adicionais do registro de emissao do relatorio, tal como descrição do relatorio.            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE   NOMEUNIT  VARCHAR2(30)                                       Nome da unit no Delphi contendo o relatório por onde foi emitido o relatorio.            OPERACIONAL                        NaN
PCLOGPROCESSBALANCETE    CONTAS2          CLOB                     Contas que estavam restritas no momento da emissao do relatorio contendo formato de grupo:conta            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*