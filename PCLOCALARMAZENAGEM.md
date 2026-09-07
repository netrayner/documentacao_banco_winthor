# 📊 Tabela: PCLOCALARMAZENAGEM

### Estrutura de Colunas e Restrições

            Tabela        Coluna Tipo/Tamanho                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOCALARMAZENAGEM      CODLOCAL NUMBER(10,0)                      Código do local de armazenagem    CHAVE PRIMÁRIA (PK)                        NaN
PCLOCALARMAZENAGEM     CODFILIAL  VARCHAR2(2)        Codigo da filial para o local de armazenagem            OPERACIONAL                        NaN
PCLOCALARMAZENAGEM     DESCRICAO VARCHAR2(40)                   Descricao do Local de armazenagem            OPERACIONAL                        NaN
PCLOCALARMAZENAGEM CODIMPRESSORA NUMBER(10,0) Codigo da impressora para este local de armazenagem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*