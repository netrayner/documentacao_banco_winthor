# 📊 Tabela: PCUSURCLI

### Estrutura de Colunas e Restrições

   Tabela        Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCUSURCLI       CODUSUR  NUMBER(4,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCUSURCLI        CODCLI  NUMBER(6,0)                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCUSURCLI      TIPOOPER  VARCHAR2(1)                                          NaN            OPERACIONAL                        NaN
PCUSURCLI CODUSURPADRAO  NUMBER(6,0) Indica o Código do RCA padrão(iniciar venda)            OPERACIONAL                        NaN
PCUSURCLI       ENVIAFV  VARCHAR2(1)          Limitar envio de informações par FV            OPERACIONAL                        NaN
PCUSURCLI    DTMXSALTER         DATE                                          NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*