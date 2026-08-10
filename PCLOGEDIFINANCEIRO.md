# 📊 Tabela: PCLOGEDIFINANCEIRO

### Estrutura de Colunas e Restrições

            Tabela      Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGEDIFINANCEIRO      CODLOG  NUMBER(20,0)                                         CHAVE PRIMARIA    CHAVE PRIMÁRIA (PK)                        NaN
PCLOGEDIFINANCEIRO       DTLOG          DATE                                 DATA DE CRIAÇÃO DO LOG            OPERACIONAL                        NaN
PCLOGEDIFINANCEIRO      ORIGEM  VARCHAR2(30)                         ORIGEM DO LOG (NOME DA TABELA)            OPERACIONAL                        NaN
PCLOGEDIFINANCEIRO       CHAVE VARCHAR2(200) CHAVE DA ORIGEM (ID DA TABELA QUE ESTÁ GRAVANDO O LOG)            OPERACIONAL                        NaN
PCLOGEDIFINANCEIRO TIPOCHAMADA   VARCHAR2(3)     TIPO DE CHAMADA (REQ - REQUISIÇÃO, RES - RESPONSE)            OPERACIONAL                        NaN
PCLOGEDIFINANCEIRO        JSON          CLOB                         JSON DA REQUISIÇÃO OU RESPONSE            OPERACIONAL                        NaN
PCLOGEDIFINANCEIRO         OBS VARCHAR2(200)                                             Observação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*