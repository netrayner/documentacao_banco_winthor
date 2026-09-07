# 📊 Tabela: PCEXCECAOUFMEDABCFARMA

### Estrutura de Colunas e Restrições

                Tabela             Coluna Tipo/Tamanho                    Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCEXCECAOUFMEDABCFARMA         CODEXCECAO  VARCHAR2(8)                      Código da Exceção    CHAVE PRIMÁRIA (PK)                        NaN
PCEXCECAOUFMEDABCFARMA         ALIQCALCPF  NUMBER(8,4) Alíquota para Cálculo do Preço Fábrica            OPERACIONAL                        NaN
PCEXCECAOUFMEDABCFARMA  DESCRICAORESUMIDA VARCHAR2(20)                     Descrição Resumida            OPERACIONAL                        NaN
PCEXCECAOUFMEDABCFARMA DESCRICAODETALHADA VARCHAR2(80)                    Descrição Detalhada            OPERACIONAL                        NaN
PCEXCECAOUFMEDABCFARMA         DESATIVADO  VARCHAR2(1)                             Desativada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*