# 📊 Tabela: PCCONFORDENACAOOSWMS_ITEM

### Estrutura de Colunas e Restrições

                   Tabela            Coluna Tipo/Tamanho            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCONFORDENACAOOSWMS_ITEM CODORDENACAOITENS  NUMBER(4,0)  Código da ordenação dos ítens    CHAVE PRIMÁRIA (PK)                        NaN
PCCONFORDENACAOOSWMS_ITEM      CODORDENACAO  NUMBER(4,0)            Código da ordenação CHAVE ESTRANGEIRA (FK)       PCCONFORDENACAOOSWMS
PCCONFORDENACAOOSWMS_ITEM    TIPO_ORDENACAO  VARCHAR2(2) Tipo da ordenação - o.s./ítens            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS_ITEM             ORDEM  NUMBER(5,0)          Sequencia dos valores            OPERACIONAL                        NaN
PCCONFORDENACAOOSWMS_ITEM             VALOR  NUMBER(5,0)                  Valor do ítem            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*