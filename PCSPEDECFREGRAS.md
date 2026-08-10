# 📊 Tabela: PCSPEDECFREGRAS

### Estrutura de Colunas e Restrições

         Tabela    Coluna   Tipo/Tamanho                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFREGRAS        ID    NUMBER(8,0)                                      Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFREGRAS    CODIGO         NUMBER                                                             Cód. da regra            OPERACIONAL                        NaN
PCSPEDECFREGRAS DESCRICAO  VARCHAR2(400)                      Descrição da conta, como "22C ¿ Licença Maternidade"            OPERACIONAL                        NaN
PCSPEDECFREGRAS     DTINI           DATE                                            Data de início do uso da regra            OPERACIONAL                        NaN
PCSPEDECFREGRAS     DTFIM           DATE                                      Data de encerramento do uso da regra            OPERACIONAL                        NaN
PCSPEDECFREGRAS CAMPO_REF   VARCHAR2(50)                     Campo de referência usado pelo PAV da Receita Federal            OPERACIONAL                        NaN
PCSPEDECFREGRAS     NIVEL    VARCHAR2(5)        Obtido dos registro da Receita Federal. Ainda não está sendo usado            OPERACIONAL                        NaN
PCSPEDECFREGRAS   FORMULA VARCHAR2(4000)                                           Fórmula para avaliação da conta            OPERACIONAL                        NaN
PCSPEDECFREGRAS  MENSAGEM  VARCHAR2(800)                  Mensagem que poderá ser exibida na validação do SPED ECF            OPERACIONAL                        NaN
PCSPEDECFREGRAS  REGISTRO   VARCHAR2(10) Registro do SPED ECF que pertence esta regra, como "M300", "M350", "N600"            OPERACIONAL                        NaN
PCSPEDECFREGRAS     CHAVE   VARCHAR2(10)                              Cód. da conta no plano de contas do SPED ECF            OPERACIONAL                        NaN
PCSPEDECFREGRAS       ANO    NUMBER(4,0)                                                         Ano de referência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*