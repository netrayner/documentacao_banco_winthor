# 📊 Tabela: PCMENSAGEMCTE

### Estrutura de Colunas e Restrições

       Tabela        Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMCTE   CODMENSAGEM  NUMBER(10,0)                                           Código da mensagem    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMCTE     DESCRICAO VARCHAR2(180)                                        Descrição da mensagem            OPERACIONAL                        NaN
PCMENSAGEMCTE       SOLUCAO          CLOB            Gravar o hint de ajuda para solução dos problemas            OPERACIONAL                        NaN
PCMENSAGEMCTE REJEICAOSEFAZ   VARCHAR2(1) Indica se a rejeição é proveniente da SEFAZ ou do DocFiscal.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*