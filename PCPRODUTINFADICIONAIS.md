# 📊 Tabela: PCPRODUTINFADICIONAIS

### Estrutura de Colunas e Restrições

               Tabela    Coluna  Tipo/Tamanho                                                        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPRODUTINFADICIONAIS   CODPROD   NUMBER(6,0)                                                          Código do produto    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTINFADICIONAIS       SEQ   NUMBER(6,0)                                                                  Sequência    CHAVE PRIMÁRIA (PK)                        NaN
PCPRODUTINFADICIONAIS DESCRICAO VARCHAR2(100)                                                                  Descrição            OPERACIONAL                        NaN
PCPRODUTINFADICIONAIS      TIPO   VARCHAR2(2) Tipo: aplicação, observação, Nº Original, Nº Original Anterior, Sinônimos.            OPERACIONAL                        NaN
PCPRODUTINFADICIONAIS     ORDEM   NUMBER(6,0)                                      Ordem de vizualização das informações            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*