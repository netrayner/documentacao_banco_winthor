# 📊 Tabela: PCPRINCIPATIVO

### Estrutura de Colunas e Restrições

        Tabela          Coluna   Tipo/Tamanho                                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRINCIPATIVO CODPRINCIPATIVO   NUMBER(10,0)                                                      NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCPRINCIPATIVO       DESCRICAO  VARCHAR2(100)                                                      NaN            OPERACIONAL                        NaN
PCPRINCIPATIVO             DCB   VARCHAR2(20)                                                      NaN            OPERACIONAL                        NaN
PCPRINCIPATIVO      DESCRICAO2 VARCHAR2(1000)                                               DESCRICAO2            OPERACIONAL                        NaN
PCPRINCIPATIVO      SUBSTANCIA    VARCHAR2(2) Lista de Classificação da Substância do Princípio ativo.            OPERACIONAL                        NaN
PCPRINCIPATIVO      DTMXSALTER           DATE                                                      NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*