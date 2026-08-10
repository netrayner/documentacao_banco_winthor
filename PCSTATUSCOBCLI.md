# 📊 Tabela: PCSTATUSCOBCLI

### Estrutura de Colunas e Restrições

        Tabela       Coluna Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSTATUSCOBCLI CODSTATUSCOB  NUMBER(4,0)                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCSTATUSCOBCLI    STATUSCOB VARCHAR2(40)                                                       NaN            OPERACIONAL                        NaN
PCSTATUSCOBCLI         TIPO  VARCHAR2(1) Definir o status da cobrança em produtivo ou improdutivo.            OPERACIONAL                        NaN
PCSTATUSCOBCLI    EXIGEDATA  VARCHAR2(1)        Define se a cobrança exige data de retorno ou não.            OPERACIONAL                        NaN
PCSTATUSCOBCLI   PRIORIDADE  NUMBER(6,0)                Define a prioridade do status de cobrança.            OPERACIONAL                        NaN
PCSTATUSCOBCLI  DIASRETORNO  NUMBER(6,0)           Indica o número de dias de retorno da cobrança.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*