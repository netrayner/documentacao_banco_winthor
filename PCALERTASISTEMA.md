# 📊 Tabela: PCALERTASISTEMA

### Estrutura de Colunas e Restrições

         Tabela     Coluna  Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCALERTASISTEMA         ID  NUMBER(10,0) Identificador do alerta    CHAVE PRIMÁRIA (PK)                        NaN
PCALERTASISTEMA   MENSAGEM VARCHAR2(250)      Mensagem do alerta            OPERACIONAL                        NaN
PCALERTASISTEMA     SCRIPT          CLOB        Script do alerta            OPERACIONAL                        NaN
PCALERTASISTEMA       TIPO VARCHAR2(250)          Tipo do alerta            OPERACIONAL                        NaN
PCALERTASISTEMA TIPOSCRIPT VARCHAR2(250)          Tipo do Script            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*