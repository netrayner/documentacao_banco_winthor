# 📊 Tabela: PCREINFR2030I

### Estrutura de Colunas e Restrições

       Tabela         Coluna  Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCREINFR2030I             ID   NUMBER(8,0)                            Identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCREINFR2030I      R2030C_ID   NUMBER(8,0) Identificador do registro 2030 cabeçalho            OPERACIONAL                        NaN
PCREINFR2030I         RECNUM  NUMBER(22,0)                  RecNum da tabela PCLANC            OPERACIONAL                        NaN
PCREINFR2030I    TIPOREPASSE   NUMBER(8,0)                          Tipo de repasse            OPERACIONAL                        NaN
PCREINFR2030I VLBRUTOREPASSE  NUMBER(12,2)                   Valor bruto do repasse            OPERACIONAL                        NaN
PCREINFR2030I     VLRETENCAO  NUMBER(12,2)                        Valor de retenção            OPERACIONAL                        NaN
PCREINFR2030I   DESCRRECURSO VARCHAR2(300)                     Descrição do recurso            OPERACIONAL                        NaN
PCREINFR2030I         STATUS VARCHAR2(100)                                   Status            OPERACIONAL                        NaN
PCREINFR2030I     RETEMVALOR   VARCHAR2(1)                              Retem valor            OPERACIONAL                        NaN
PCREINFR2030I    RETIFICACAO   VARCHAR2(1)     Controle de processo em retificação.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*