# 📊 Tabela: PCRETORNOTRE

### Estrutura de Colunas e Restrições

      Tabela     Coluna  Tipo/Tamanho                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRETORNOTRE         ID  NUMBER(10,0)                       Identificador da tabela    CHAVE PRIMÁRIA (PK)                        NaN
PCRETORNOTRE       TIPO VARCHAR2(100)            TIPO DA MENSAGEM DOSISTEMA EXTERNO            OPERACIONAL                        NaN
PCRETORNOTRE    ENVIADO VARCHAR2(100)          Identifica se a mensagem foi enviada            OPERACIONAL                        NaN
PCRETORNOTRE IDMENSAGEM VARCHAR2(100)             ID da mensagem do sistema externo            OPERACIONAL                        NaN
PCRETORNOTRE     CODIGO  NUMBER(10,0) Código a ser retornado para o sistema externo            OPERACIONAL                        NaN
PCRETORNOTRE   IDVIAGEM  NUMBER(10,0)    Identificador da viagem do sistema externo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*