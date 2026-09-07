# 📊 Tabela: PCOCORBCI

### Estrutura de Colunas e Restrições

   Tabela           Coluna Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCOCORBCI         NUMBANCO  NUMBER(4,0)                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOCORBCI    CODOCORRENCIA  VARCHAR2(2)                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOCORBCI CODSUBOCORRENCIA  VARCHAR2(4)                                                                       NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCOCORBCI        DESCRICAO VARCHAR2(80)                                                                       NaN            OPERACIONAL                        NaN
PCOCORBCI        TIPOOCORR  NUMBER(3,0)                                    Indica o tipo da ocorrência magnética.    CHAVE PRIMÁRIA (PK)                        NaN
PCOCORBCI         CODBANCO  NUMBER(4,0)                                             Código do Banco da Ocorrência            OPERACIONAL                        NaN
PCOCORBCI         CARTORIO  VARCHAR2(1)     Usado quando o banco retorna na subocorrencia se deve cobrar cartório            OPERACIONAL                        NaN
PCOCORBCI         PROTESTO  VARCHAR2(1) Usado quando o banco retorna na subocorrencia se o título foi protestado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*