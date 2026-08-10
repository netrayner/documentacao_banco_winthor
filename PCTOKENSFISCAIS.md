# 📊 Tabela: PCTOKENSFISCAIS

### Estrutura de Colunas e Restrições

         Tabela               Coluna  Tipo/Tamanho                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTOKENSFISCAIS       CODAUTORIZADOR  NUMBER(10,0)                                Matricula do usuario que liberou o token            OPERACIONAL                        NaN
PCTOKENSFISCAIS CODUSUARIOAUTORIZADO  NUMBER(10,0)                                 Matricula do usuário que foi autorizado            OPERACIONAL                        NaN
PCTOKENSFISCAIS                TOKEN VARCHAR2(100) Identificado do dispositivo que esta sendo liberado a acessar o Winthor            OPERACIONAL                        NaN
PCTOKENSFISCAIS               STATUS  VARCHAR2(20)                               Status do token(Valores: ATIVO/BLOQUEADO)            OPERACIONAL                        NaN
PCTOKENSFISCAIS             PROCESSO  VARCHAR2(20)                       Identificador do processo que o token terá acesso            OPERACIONAL                        NaN
PCTOKENSFISCAIS         NUMSEQUENCIA  NUMBER(10,0)                                           Número de sequencia da tabela    CHAVE PRIMÁRIA (PK)                        NaN

---
*Documentação gerada automaticamente.*