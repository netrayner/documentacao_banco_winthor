# 📊 Tabela: PCFORMCONFIG

### Estrutura de Colunas e Restrições

      Tabela    Coluna  Tipo/Tamanho                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCFORMCONFIG    CODIGO   NUMBER(8,0)                                   NaN    CHAVE PRIMÁRIA (PK)                        NaN
PCFORMCONFIG    ROTINA   NUMBER(8,0)                                   NaN            OPERACIONAL                        NaN
PCFORMCONFIG MATRICULA   NUMBER(8,0)                                   NaN            OPERACIONAL                        NaN
PCFORMCONFIG      NOME VARCHAR2(250)                                   NaN            OPERACIONAL                        NaN
PCFORMCONFIG   ARQUIVO          BLOB                                   NaN            OPERACIONAL                        NaN
PCFORMCONFIG      JSON          CLOB JSON com a configuração do formulário            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*