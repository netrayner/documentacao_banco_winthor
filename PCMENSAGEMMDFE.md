# 📊 Tabela: PCMENSAGEMMDFE

### Estrutura de Colunas e Restrições

        Tabela        Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMMDFE   CODMENSAGEM   NUMBER(6,0)                                           Código da mensagem    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMMDFE     DESCRICAO VARCHAR2(300)                                          Solução da mensagem            OPERACIONAL                        NaN
PCMENSAGEMMDFE       SOLUCAO          CLOB                                                          NaN            OPERACIONAL                        NaN
PCMENSAGEMMDFE REJEICAOSEFAZ   VARCHAR2(1) Indica se a rejeição é proveniente da SEFAZ ou do DocFiscal.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*