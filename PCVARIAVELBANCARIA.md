# 📊 Tabela: PCVARIAVELBANCARIA

### Estrutura de Colunas e Restrições

            Tabela       Coluna  Tipo/Tamanho    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCVARIAVELBANCARIA       CODIGO  NUMBER(10,0)     Codigo da variavel    CHAVE PRIMÁRIA (PK)                        NaN
PCVARIAVELBANCARIA         NOME VARCHAR2(100)       Nome da variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA    DESCRICAO VARCHAR2(255)  Descrição da variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA TIPOVARIAVEL  VARCHAR2(15)       Tipo da variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA    TIPODADOS  VARCHAR2(15)          Tipo De dados            OPERACIONAL                        NaN
PCVARIAVELBANCARIA TIPOCONTEUDO  VARCHAR2(15)       Tipo de conteudo            OPERACIONAL                        NaN
PCVARIAVELBANCARIA       STATUS  VARCHAR2(15)        Status variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA   FINALIDADE  VARCHAR2(20) finalidade da variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA     PROCESSO  VARCHAR2(30)   processo da variavel            OPERACIONAL                        NaN
PCVARIAVELBANCARIA     CONTEUDO          CLOB   Conteudo da variavel            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*