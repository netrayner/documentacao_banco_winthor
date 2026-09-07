# 📊 Tabela: PCSSERVFATATIVO

### Estrutura de Colunas e Restrições

         Tabela    Coluna  Tipo/Tamanho                                                                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSSERVFATATIVO     ATIVO   VARCHAR2(1)                                                               Indica se a instancia do servidor de faturamento está ativa.            OPERACIONAL                        NaN
PCSSERVFATATIVO   MAQUINA VARCHAR2(100)                                                 Indica qual a maquina que esteve, ou está ativa o servidor de faturamento.            OPERACIONAL                        NaN
PCSSERVFATATIVO USUARIOSO VARCHAR2(100)                               Indica qual o usuário do sistema operacional está ou esteve ativo o servidor de faturamento.            OPERACIONAL                        NaN
PCSSERVFATATIVO        ID   NUMBER(6,0)                                                                       Identificador único para controle de chave primaria.    CHAVE PRIMÁRIA (PK)                        NaN
PCSSERVFATATIVO      BEAT  TIMESTAMP(6) Campo Timestamp para verificar se o servidor de faturamento esta inativo caso o mesmo tenha sido fechado de forma abrupta.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*