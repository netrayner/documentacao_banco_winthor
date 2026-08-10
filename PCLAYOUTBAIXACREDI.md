# 📊 Tabela: PCLAYOUTBAIXACREDI

### Estrutura de Colunas e Restrições

            Tabela         Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTBAIXACREDI         CODIGO  NUMBER(8,0)          Código do item do layout    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTBAIXACREDI      CODLAYOUT  NUMBER(8,0)                  Código do layout CHAVE ESTRANGEIRA (FK)          PCLAYOUTBAIXACRED
PCLAYOUTBAIXACREDI      DESCRICAO VARCHAR2(80)       Descrição do item do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI          SIGLA VARCHAR2(30)   Sigla para identificar o layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI           TIPO VARCHAR2(10)                    Tipo do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI POSICAOINICIAL  NUMBER(6,0)         Posição inicial do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI   POSICAOFINAL  NUMBER(6,0)           Posição final do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI        TAMANHO  NUMBER(6,0)      Tamanho da posição do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI     OBSERVACAO VARCHAR2(40)     Observação referente ao campo            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI    POSICAOFIXA  NUMBER(3,0) Posição fixa no layout do arquivo            OPERACIONAL                        NaN
PCLAYOUTBAIXACREDI      VALORFIXO VARCHAR2(25)   Valor fixo no layout do arquivo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*