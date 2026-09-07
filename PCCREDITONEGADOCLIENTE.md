# 📊 Tabela: PCCREDITONEGADOCLIENTE

### Estrutura de Colunas e Restrições

                Tabela           Coluna   Tipo/Tamanho     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCREDITONEGADOCLIENTE           CODCLI    NUMBER(9,0)       Código do cliente    CHAVE PRIMÁRIA (PK)                        NaN
PCCREDITONEGADOCLIENTE DATAHORAINCLUSAO           DATE Data e hora da inclusão    CHAVE PRIMÁRIA (PK)                        NaN
PCCREDITONEGADOCLIENTE            VALOR   NUMBER(10,2)                   Valor            OPERACIONAL                        NaN
PCCREDITONEGADOCLIENTE           MOTIVO VARCHAR2(2000)                  Motivo            OPERACIONAL                        NaN
PCCREDITONEGADOCLIENTE  CODFUNCINCLUSAO    NUMBER(8,0)    Funcionário inclusão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*