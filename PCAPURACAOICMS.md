# 📊 Tabela: PCAPURACAOICMS

### Estrutura de Colunas e Restrições

        Tabela     Coluna  Tipo/Tamanho                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAPURACAOICMS      LIVRO   VARCHAR2(4) Tipo de livro selecionado para impressão.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMS  CODFILIAL   VARCHAR2(2)                Código da filial apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMS        MES   NUMBER(2,0)                          Mês de apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMS        ANO   NUMBER(4,0)                          Ano de apuração.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMS  NOMECAMPO  VARCHAR2(20)                     Nome do campo setado.    CHAVE PRIMÁRIA (PK)                        NaN
PCAPURACAOICMS VALORCAMPO VARCHAR2(200)                    Valor do campo setado.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*