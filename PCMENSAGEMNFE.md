# 📊 Tabela: PCMENSAGEMNFE

### Estrutura de Colunas e Restrições

       Tabela        Coluna  Tipo/Tamanho                                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENSAGEMNFE   CODMENSAGEM   NUMBER(6,0)                                                          NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCMENSAGEMNFE     DESCRICAO VARCHAR2(180)                                                          NaN            OPERACIONAL                        NaN
PCMENSAGEMNFE       SOLUCAO          CLOB            Gravar o hint de ajuda para solução dos problemas            OPERACIONAL                        NaN
PCMENSAGEMNFE REJEICAOSEFAZ   VARCHAR2(1) Indica se a rejeição é proveniente da SEFAZ ou do DocFiscal.    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*