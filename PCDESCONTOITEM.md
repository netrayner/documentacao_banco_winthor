# 📊 Tabela: PCDESCONTOITEM

### Estrutura de Colunas e Restrições

        Tabela      Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDESCONTOITEM CODDESCONTO  NUMBER(8,0)              Código da politica de desconto            OPERACIONAL                        NaN
PCDESCONTOITEM        TIPO  VARCHAR2(3)                    Tipo do item do desconto            OPERACIONAL                        NaN
PCDESCONTOITEM  VALOR_ALFA VARCHAR2(30) Indica o item filho com chave Alfa Numerica            OPERACIONAL                        NaN
PCDESCONTOITEM   VALOR_NUM NUMBER(18,6)      Indica o item filho com chave numérico            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*