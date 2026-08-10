# 📊 Tabela: PCFORMULATINTA

### Estrutura de Colunas e Restrições

        Tabela                Coluna  Tipo/Tamanho                                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMULATINTA            CODMAQUINA   NUMBER(4,0)                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTA        CHAVEPRINCIPAL  VARCHAR2(40)                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTA          CODMONTADORA  VARCHAR2(40)                                                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTA            CODFORMULA  VARCHAR2(25)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA              CODLINHA  VARCHAR2(40)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA          CODSIGLAPAIS  VARCHAR2(40)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA          CODQUALIDADE  VARCHAR2(40)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA           ALTERNATIVA  VARCHAR2(10)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA           DESCFORMULA  VARCHAR2(70)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA                   ANO   NUMBER(4,0)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA PESOESPECIFICOFORMULA NUMBER(24,18)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA  CODIGOOEM_FABRICANTE VARCHAR2(400)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA               CODBASE  VARCHAR2(40)                                                                   NaN            OPERACIONAL                        NaN
PCFORMULATINTA            ANOINICIAL   NUMBER(4,0)        Determina o ano inicial dos carros que a cor da tinta atende.             OPERACIONAL                        NaN
PCFORMULATINTA              ANOFINAL   NUMBER(4,0)          Determina o ano final dos carros que a cor da tinta atende.             OPERACIONAL                        NaN
PCFORMULATINTA           NOMEPRODUTO VARCHAR2(100)    Identifica o nome do produto do qual a formula de tinta pertence.             OPERACIONAL                        NaN
PCFORMULATINTA        NOMESUBPRODUTO VARCHAR2(100) Identifica o nome do subproduto do qual a formula de tinta pertence.             OPERACIONAL                        NaN
PCFORMULATINTA              SITUACAO   VARCHAR2(1)                                          situação da formula de tinta    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMULATINTA              CODGRUPO  VARCHAR2(10)                                                CÓD. DO GRUPO DA TINTA            OPERACIONAL                        NaN
PCFORMULATINTA            DTULTALTER          DATE                                                     Data de alteração            OPERACIONAL                        NaN
PCFORMULATINTA          DTIMPORTACAO          DATE                                                    Data de importação            OPERACIONAL                        NaN
PCFORMULATINTA    AUXILIARIMPORTACAO VARCHAR2(150)                                                   Auxiliar Importação            OPERACIONAL                        NaN
PCFORMULATINTA                   OBS VARCHAR2(200)                                        OBSERVAÇÃO DA FORMULA DE TINTA            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*