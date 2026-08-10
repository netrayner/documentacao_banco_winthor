# 📊 Tabela: PCTABTRIB

### Estrutura de Colunas e Restrições

   Tabela                   Coluna  Tipo/Tamanho                                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTABTRIB                  CODPROD   NUMBER(6,0)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCTABTRIB              CODFILIALNF   VARCHAR2(2)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCTABTRIB                UFDESTINO   VARCHAR2(2)                                                    NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCTABTRIB                    CODST   NUMBER(4,0)                                                    NaN            OPERACIONAL                        NaN
PCTABTRIB               DTULTALTER          DATE Utilizado para permitir carga parcial pela rotina 2001            OPERACIONAL                        NaN
PCTABTRIB         CODTRIBPISCOFINS   NUMBER(4,0)                           Código Tributação Pis/Cofins            OPERACIONAL                        NaN
PCTABTRIB          IDENTIFICARTRIB VARCHAR2(200)                    Indentificação do arquivo importado            OPERACIONAL                        NaN
PCTABTRIB       IDENTIFICARTRIBIPI VARCHAR2(200)                         Código de identificação do IPI            OPERACIONAL                        NaN
PCTABTRIB IDENTIFICARTRIBPISCOFINS VARCHAR2(200)                  Código de identificação do PIS/COFINS            OPERACIONAL                        NaN
PCTABTRIB               DTMXSALTER          DATE                                                    NaN            OPERACIONAL                        NaN
PCTABTRIB      CODFILIALINTEGRACAO   NUMBER(3,0)                         Código da Filial de Integração            OPERACIONAL                        NaN
PCTABTRIB                DTALTERC5  TIMESTAMP(6)                                         Data alteração            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*