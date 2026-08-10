# 📊 Tabela: PCSPEDECFPLANOCONTAS

### Estrutura de Colunas e Restrições

              Tabela       Coluna   Tipo/Tamanho                                                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSPEDECFPLANOCONTAS           ID    NUMBER(8,0)                                                      Identificador único do registro (PK)    CHAVE PRIMÁRIA (PK)                        NaN
PCSPEDECFPLANOCONTAS     CODCONTA   VARCHAR2(40)                                      Cód. da conta com pontos separadores, como "3.01.02"            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS  CODCONTANUM  NUMBER(25,20)         Cód. da conta no formato numérico, usado em ordenações. Ex: "9.12.34" será 9,1234            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS    DESCRICAO  VARCHAR2(400)                                    Descrição da conta, como "Lucro Líquido Antes do IRPJ"            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS        DTINI           DATE                                                            Data de início do uso da conta            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS        DTFIM           DATE                                                      Data de encerramento do uso da conta            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS        ORDEM    NUMBER(5,0)         Ordem de apresentação da conta no plano, conforme os registros da Receita Federal            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS         TIPO    VARCHAR2(3) A conta pode ser do tipo R-Resumo, E-Editável, CA-Calculado ou CNA-Calculado não editável            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS      FORMATO    VARCHAR2(3)                                                  Pode ser vazio ou NS-Nº decimal c/ sinal            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS     LINHAECF    NUMBER(5,0)                                                   Número da linha que será gravado no ECF            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS      FORMULA VARCHAR2(4000)                                                             Pode ser vazio ou uma fórmula            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS TIPOLANCSPED    VARCHAR2(3)            Info para o SPED. Pode ser R-Resumo, L-Lucro, A-Adição, E-Exclusão, P-Prejuízo            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS     REGISTRO   VARCHAR2(10)                 Registro do SPED ECF que pertence esta conta, como "M300", "M350", "N600"            OPERACIONAL                        NaN
PCSPEDECFPLANOCONTAS          ANO    NUMBER(4,0)                                                                         Ano de referência            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*