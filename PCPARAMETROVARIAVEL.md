# 📊 Tabela: PCPARAMETROVARIAVEL

### Estrutura de Colunas e Restrições

             Tabela      Coluna Tipo/Tamanho          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPARAMETROVARIAVEL      CODIGO NUMBER(10,0)         Código identificador    CHAVE PRIMÁRIA (PK)                        NaN
PCPARAMETROVARIAVEL  CODPOSICAO NUMBER(10,0) Código da variavel no boleto            OPERACIONAL                        NaN
PCPARAMETROVARIAVEL CODVARIAVEL NUMBER(10,0)           Código da variável CHAVE ESTRANGEIRA (FK)           PCVARIAVELBOLETO
PCPARAMETROVARIAVEL        NOME VARCHAR2(50)            Nome do parametro            OPERACIONAL                        NaN
PCPARAMETROVARIAVEL     FORMULA         CLOB           Valor do parâmetro            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*