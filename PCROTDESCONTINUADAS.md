# 📊 Tabela: PCROTDESCONTINUADAS

### Estrutura de Colunas e Restrições

             Tabela    Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCROTDESCONTINUADAS    CODIGO  NUMBER(6,0)               Código sequencial do registro.    CHAVE PRIMÁRIA (PK)                        NaN
PCROTDESCONTINUADAS CODROTINA  NUMBER(6,0)              Código da rotina descontinuada.            OPERACIONAL                        NaN
PCROTDESCONTINUADAS      NOME VARCHAR2(40)                Nome da rotina descontinuada.            OPERACIONAL                        NaN
PCROTDESCONTINUADAS    MOTIVO         CLOB Motivo pela qual a rotina foi descontinuada.            OPERACIONAL                        NaN
PCROTDESCONTINUADAS      ACAO         CLOB           Ações que o usuário deve realizar.            OPERACIONAL                        NaN
PCROTDESCONTINUADAS      DATA         DATE            Data da descontinuação da rotina.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*