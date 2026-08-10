# 📊 Tabela: PCONBOARDDIVCONTENT

### Estrutura de Colunas e Restrições

             Tabela       Coluna  Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCONBOARDDIVCONTENT    IDCONTENT   NUMBER(6,0)                          Código do Conteúdo    CHAVE PRIMÁRIA (PK)                        NaN
PCONBOARDDIVCONTENT        IDDIV   NUMBER(6,0) Código da DIV a qual o Conteúdo pertence FK            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT    SEQUENCIA   NUMBER(6,0)                       Sequencia do Conteúdo            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT   COMPONENTE  VARCHAR2(20)                 Identificação do Componente            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT      BASE64I          CLOB                 Ícone Principal do Conteúdo            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT     BASE64II          CLOB              Ícone Secundário do Componente            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT       TITULO VARCHAR2(200)                          Título do Conteúdo            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT    DESCRICAO VARCHAR2(200)                       Descrição do Conteúdo            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT  OBSERVACAOI VARCHAR2(300)                                Observação I            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT OBSERVACAOII VARCHAR2(300)                               Observação II            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT         ACAO VARCHAR2(100)                                Nome da Ação            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT      CHECKED   VARCHAR2(1)                                 Selecionado            OPERACIONAL                        NaN
PCONBOARDDIVCONTENT       STATUS   VARCHAR2(1)                        Status do Componente            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*