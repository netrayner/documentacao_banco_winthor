# 📊 Tabela: PCSERASA_REGISTRO

### Estrutura de Colunas e Restrições

           Tabela      Coluna  Tipo/Tamanho           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSERASA_REGISTRO          ID  NUMBER(10,0)    Código interno da consulta CHAVE ESTRANGEIRA (FK)         PCSERASA_CONSULTAS
PCSERASA_REGISTRO        TIPO VARCHAR2(100)                Tipo do layout            OPERACIONAL                        NaN
PCSERASA_REGISTRO   NOME_TIPO VARCHAR2(100)  Tipo de informação do layout            OPERACIONAL                        NaN
PCSERASA_REGISTRO    SEQ_TIPO  NUMBER(10,0)            Sequencial interno            OPERACIONAL                        NaN
PCSERASA_REGISTRO  NOME_CAMPO VARCHAR2(400)            Descrição do campo            OPERACIONAL                        NaN
PCSERASA_REGISTRO    SEQ_NOME   VARCHAR2(3) Sequencial do campo no layout            OPERACIONAL                        NaN
PCSERASA_REGISTRO VALOR_CAMPO VARCHAR2(400)               Valor importado            OPERACIONAL                        NaN
PCSERASA_REGISTRO       LINHA   VARCHAR2(6)    Linha do arquivo importada            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*