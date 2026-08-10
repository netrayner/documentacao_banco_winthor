# 📊 Tabela: PCDEMONSTRATIVOCTB

### Estrutura de Colunas e Restrições

            Tabela              Coluna Tipo/Tamanho                                                                           Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDEMONSTRATIVOCTB          CODDEMONST  NUMBER(6,0)                                                  Campo chave que identifica o demonstrativo.     CHAVE PRIMÁRIA (PK)                        NaN
PCDEMONSTRATIVOCTB           DESCRICAO VARCHAR2(50)                                                          Campo que descreve o demonstrativo.             OPERACIONAL                        NaN
PCDEMONSTRATIVOCTB VALORNEGATIVOEXIBIR  VARCHAR2(1) Campo que identifica se valores negativos deverão exibir sinal negativo ou entre parênteses.             OPERACIONAL                        NaN
PCDEMONSTRATIVOCTB                 DFC  VARCHAR2(1)                                                                                   Compor DFC.            OPERACIONAL                        NaN
PCDEMONSTRATIVOCTB     NOTAEXPLICATIVA         CLOB                                              Informações da nota explicativa do demonstrativo            OPERACIONAL                        NaN
PCDEMONSTRATIVOCTB  DESCRICAOIMPRESSAO VARCHAR2(60)                                                                        Descrição da impressão            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*