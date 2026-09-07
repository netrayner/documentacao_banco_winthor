# 📊 Tabela: PCCONTAMASTER

### Estrutura de Colunas e Restrições

       Tabela         Coluna Tipo/Tamanho                      Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONTAMASTER CODCONTAMASTER NUMBER(10,0)           Identificador da conta master.    CHAVE PRIMÁRIA (PK)                        NaN
PCCONTAMASTER      DESCRICAO VARCHAR2(40)               Descrição da conta master.            OPERACIONAL                        NaN
PCCONTAMASTER      ORDENACAO  NUMBER(6,0) Define o codigo do tipo de conta master.            OPERACIONAL                        NaN
PCCONTAMASTER   CODTIPOCONTA  NUMBER(6,0)        Ordenação de exibição das contas.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*