# 📊 Tabela: PCTERMINALCONSULTAI

### Estrutura de Colunas e Restrições

             Tabela       Coluna Tipo/Tamanho                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTERMINALCONSULTAI   ENDERECOIP VARCHAR2(15)                Endereço ip do terminal.            OPERACIONAL                        NaN
PCTERMINALCONSULTAI    DESCRICAO VARCHAR2(60)      Descrição do terminal de consulta.            OPERACIONAL                        NaN
PCTERMINALCONSULTAI TIPOAPARELHO VARCHAR2(30)                      Tipo de aparelho .            OPERACIONAL                        NaN
PCTERMINALCONSULTAI    CODFILIAL  VARCHAR2(2)                       Código da filial.            OPERACIONAL                        NaN
PCTERMINALCONSULTAI    NUMREGIAO  NUMBER(4,0)                       Número da região.            OPERACIONAL                        NaN
PCTERMINALCONSULTAI  COLUNAPRECO  NUMBER(1,0) Coluna de preço utilizada pelo terminal            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*