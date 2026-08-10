# 📊 Tabela: PCDOCIMP

### Estrutura de Colunas e Restrições

  Tabela    Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDOCIMP    CODIGO  NUMBER(6,0) Código sequencial de documento ou modalidade    CHAVE PRIMÁRIA (PK)                        NaN
PCDOCIMP DESCRICAO VARCHAR2(80)         Descrição do documento ou modalidade            OPERACIONAL                        NaN
PCDOCIMP    PADRAO  VARCHAR2(1)              Define se é um documento padrão            OPERACIONAL                        NaN
PCDOCIMP   TIPODOC  VARCHAR2(1)          Define o tipo do documento: [D e M]            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*