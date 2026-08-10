# 📊 Tabela: PCBANCOMOEDA

### Estrutura de Colunas e Restrições

      Tabela           Coluna Tipo/Tamanho        Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCBANCOMOEDA         CODBANCO  NUMBER(4,0)  Indica o código do banco.            OPERACIONAL                        NaN
PCBANCOMOEDA         CODMOEDA  VARCHAR2(4)  Indica o código da moeda.            OPERACIONAL                        NaN
PCBANCOMOEDA CODCONTACONTABIL VARCHAR2(12)  Indica o código contábil.            OPERACIONAL                        NaN
PCBANCOMOEDA        CODFILIAL  VARCHAR2(2)          Código da Filial.            OPERACIONAL                        NaN
PCBANCOMOEDA    CODPLANOCONTA  NUMBER(5,0) Código do Plano de Contas.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*