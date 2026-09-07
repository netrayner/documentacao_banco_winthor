# 📊 Tabela: PCPOLITICADESCVALOR

### Estrutura de Colunas e Restrições

             Tabela          Coluna Tipo/Tamanho                                                                  Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCPOLITICADESCVALOR CODPOLITICADESC NUMBER(10,0)                                  Código da Política de Desconto por Valor de Pedido.    CHAVE PRIMÁRIA (PK)                        NaN
PCPOLITICADESCVALOR       CODFILIAL  VARCHAR2(2)                                                         Código da Filial (opcional).            OPERACIONAL                        NaN
PCPOLITICADESCVALOR       NUMREGIAO  NUMBER(4,0)                                                         Número da Região (opcional).            OPERACIONAL                        NaN
PCPOLITICADESCVALOR        DTINICIO         DATE                                    Data de Início do Período de Vigência (opcional).            OPERACIONAL                        NaN
PCPOLITICADESCVALOR           DTFIM         DATE                                        Data Final do Período de Vigência (opcional).            OPERACIONAL                        NaN
PCPOLITICADESCVALOR         CODEPTO  NUMBER(6,0)                                                              Código do Departamento.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR          CODSEC  NUMBER(6,0)                                                                     Código da Seção.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR      VLMINVENDA NUMBER(14,2)                                                  Valor mínimo de venda para a faixa.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR      VLMAXVENDA NUMBER(14,2)                                                  Valor máximo de venda para a faixa.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR         PERDESC  NUMBER(8,2)                                                              Percentual de Desconto.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR CODFUNCCADASTRO  NUMBER(8,0) Código do funcionário que criou a faixa da política de desconto por valor de pedido.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR      DTCADASTRO         DATE                                        Data de criação da Faixa: gravar data e hora.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR CODFUNCULTALTER  NUMBER(8,0) Código do último funcionário que alterou a política de desconto por valor de pedido.            OPERACIONAL                        NaN
PCPOLITICADESCVALOR      DTULTALTER         DATE                Data da última alteração na política de desconto por valor de pedido.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*