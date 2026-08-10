# 📊 Tabela: PCIMPRESSORAS

### Estrutura de Colunas e Restrições

       Tabela          Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCIMPRESSORAS          CODIMP NUMBER(10,0)              Código da Impressora    CHAVE PRIMÁRIA (PK)                        NaN
PCIMPRESSORAS       DESCRICAO VARCHAR2(60)            Descição da Impressora            OPERACIONAL                        NaN
PCIMPRESSORAS      IMPRESSORA VARCHAR2(60)        Caminho Impressora na Rede            OPERACIONAL                        NaN
PCIMPRESSORAS       CODFILIAL  VARCHAR2(2)                     Codigo Filial CHAVE ESTRANGEIRA (FK)                   PCFILIAL
PCIMPRESSORAS         SERVIMP NUMBER(10,0)   Código do Servidor de impressão            OPERACIONAL                        NaN
PCIMPRESSORAS   CODIMPSERVIMP NUMBER(10,0)   Código do Servidor de impressão            OPERACIONAL                        NaN
PCIMPRESSORAS IMPRESSORAATIVA  VARCHAR2(1) Define se a impressora está ativa            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*