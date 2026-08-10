# 📊 Tabela: PCMENUITEM

### Estrutura de Colunas e Restrições

    Tabela    Coluna Tipo/Tamanho                                   Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMENUITEM        ID VARCHAR2(50)              Função geral do elemento. Ex : Cadastros            OPERACIONAL                        NaN
PCMENUITEM    INDICE  NUMBER(8,0) Classificação de em qual grupo o elemento se encontra            OPERACIONAL                        NaN
PCMENUITEM      TIPO VARCHAR2(50)              Categoria do elemento. Ex: Rotina,Pagina            OPERACIONAL                        NaN
PCMENUITEM     VALOR VARCHAR2(50)    Valor expressado pelo elemento. Ex : 6001, Comprar            OPERACIONAL                        NaN
PCMENUITEM DESCRICAO VARCHAR2(50)   Observações gerais de ajuda, a respeito do elemento            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*