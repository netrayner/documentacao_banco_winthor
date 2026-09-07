# 📊 Tabela: PCTIPOLAYOUT

### Estrutura de Colunas e Restrições

      Tabela             Coluna Tipo/Tamanho               Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCTIPOLAYOUT             CODIGO  NUMBER(8,0)             Código do tipo layout    CHAVE PRIMÁRIA (PK)                        NaN
PCTIPOLAYOUT          DESCRICAO VARCHAR2(60)       Descrição do tipo do layout            OPERACIONAL                        NaN
PCTIPOLAYOUT               TIPO  VARCHAR2(5)                    Tipo do layout            OPERACIONAL                        NaN
PCTIPOLAYOUT          CODLAYOUT  NUMBER(8,0)                  Código do layout CHAVE ESTRANGEIRA (FK)          PCLAYOUTBAIXACRED
PCTIPOLAYOUT ORDEMPROCESSAMENTO  NUMBER(3,0) Ordem de processamento do arquivo            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*