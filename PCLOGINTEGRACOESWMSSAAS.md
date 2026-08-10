# 📊 Tabela: PCLOGINTEGRACOESWMSSAAS

### Estrutura de Colunas e Restrições

                 Tabela        Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLOGINTEGRACOESWMSSAAS          DATA          DATE                     Data do log            OPERACIONAL                        NaN
PCLOGINTEGRACOESWMSSAAS         PATCH VARCHAR2(100)               Patch do endpoint            OPERACIONAL                        NaN
PCLOGINTEGRACOESWMSSAAS          BODY          CLOB Corpo da request ou da response            OPERACIONAL                        NaN
PCLOGINTEGRACOESWMSSAAS          TIPO  VARCHAR2(50)                Tipo de operação            OPERACIONAL                        NaN
PCLOGINTEGRACOESWMSSAAS     DESCRICAO VARCHAR2(500)               Descrição do log             OPERACIONAL                        NaN
PCLOGINTEGRACOESWMSSAAS IDENTIFICADOR VARCHAR2(100)      Identificador do documento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*