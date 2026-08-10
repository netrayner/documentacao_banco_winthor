# 📊 Tabela: PCLOG_TRIBUTACAO_PROGRAMADA

### Estrutura de Colunas e Restrições

                     Tabela          Coluna  Tipo/Tamanho                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOG_TRIBUTACAO_PROGRAMADA              ID  NUMBER(22,0)                                      Identificador do registro    CHAVE PRIMÁRIA (PK)                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA            DATA          DATE                                        Data de registro do log            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA          TABELA VARCHAR2(100)                                        Tabela de origem do log            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA         COLUNA1 VARCHAR2(100)                    Coluna referente a chave primária da tabela            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA          CHAVE1 VARCHAR2(100)                    Valor referente da chave primária da tabela            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA         COLUNA2 VARCHAR2(100) Coluna referente a chave primária da tabela caso seja composta            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA          CHAVE2 VARCHAR2(100) Valor referente da chave primária da tabela caso seja composta            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA         COLUNA3 VARCHAR2(100) Coluna referente a chave primária da tabela caso seja composta            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA          CHAVE3 VARCHAR2(100) Valor referente da chave primária da tabela caso seja composta            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA DADOSANTERIORES          CLOB             Dados anteriores que estavam no registro da tabela            OPERACIONAL                        NaN
PCLOG_TRIBUTACAO_PROGRAMADA      DADOSNOVOS          CLOB          Dados novos que foram imputados no registro da tabela            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*