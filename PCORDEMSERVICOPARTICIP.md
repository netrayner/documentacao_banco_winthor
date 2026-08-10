# 📊 Tabela: PCORDEMSERVICOPARTICIP

### Estrutura de Colunas e Restrições

                Tabela     Coluna  Tipo/Tamanho                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCORDEMSERVICOPARTICIP      NUMOS   NUMBER(6,0) India o número da Ordem de Serviço    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMSERVICOPARTICIP     CODIGO   NUMBER(6,0) Indica a matricula do particpante.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMSERVICOPARTICIP       TIPO   VARCHAR2(1)     Indica o tipo do participante.    CHAVE PRIMÁRIA (PK)                        NaN
PCORDEMSERVICOPARTICIP     CODCLI   NUMBER(6,0)                 Código do cliente.            OPERACIONAL                        NaN
PCORDEMSERVICOPARTICIP COMENTARIO VARCHAR2(500)    Comentário para o participante.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*