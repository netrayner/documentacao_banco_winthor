# 📊 Tabela: PCLAYOUTBAIXACRED

### Estrutura de Colunas e Restrições

           Tabela          Coluna  Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTBAIXACRED          CODIGO   NUMBER(8,0)                                                                               Código do layout    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTBAIXACRED       DESCRICAO VARCHAR2(150)                                                                            Descrição do layout            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED          VERSAO  VARCHAR2(25)                                                                              Versão do arquivo            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED        TIPODADO   VARCHAR2(1)                                                              Define o tipo de dados CSV ou TXT            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED     DELIMITADOR   VARCHAR2(1)                                                                           Caracter delimitador            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED          MARGEM   NUMBER(4,2)                            Campo indica o valor aceito na diferença durante a baixa automatica            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED   LAYOUTPROPRIO   VARCHAR2(1)                                                                   Indica se o layout é próprio            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED     USANUMCUPOM   VARCHAR2(1)                                                                          Usa o número do cupom            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED USACODLOJASITEF   VARCHAR2(1)                             Usa o CodLojaSitef cadastrado para identificar a filial do Título.            OPERACIONAL                        NaN
PCLAYOUTBAIXACRED      MARGEMDATA   NUMBER(2,0) Valor de dias de margem para vinculo entre registro de arquivo de retorno e título do sistema.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*