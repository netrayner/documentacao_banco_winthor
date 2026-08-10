# 📊 Tabela: PCRELFISCAL

### Estrutura de Colunas e Restrições

     Tabela          Coluna  Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELFISCAL    CODRELATORIO   NUMBER(4,0)              Código do Relatório.    CHAVE PRIMÁRIA (PK)                        NaN
PCRELFISCAL          TITULO VARCHAR2(100)              Titulo do Relatório.            OPERACIONAL                        NaN
PCRELFISCAL       SUBTITULO VARCHAR2(100)          Sub Titulo do Relatório.            OPERACIONAL                        NaN
PCRELFISCAL EXIBETOTALGRUPO   VARCHAR2(1) Indica se exibe o total do geral.            OPERACIONAL                        NaN
PCRELFISCAL EXIBETOTALGERAL   VARCHAR2(1)                               NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*