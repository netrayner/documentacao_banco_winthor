# 📊 Tabela: PCLFREGE340

### Estrutura de Colunas e Restrições

     Tabela     Coluna Tipo/Tamanho                                                                                                Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFREGE340     CODREG  NUMBER(6,0)                                      Código do Registro.|Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFREGE340  CODFILIAL  VARCHAR2(2)                                          Código da Filial do relacionamento.|Campo do tipo caracter, de tamanho 2.            OPERACIONAL                        NaN
PCLFREGE340       DATA         DATE                                                                Data do Lançamento do registro.|Campo do tipo data.            OPERACIONAL                        NaN
PCLFREGE340   VLAJUSTE NUMBER(15,2)                        Valor do Lançamento do Ajuste.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE340     NUMDOC VARCHAR2(20)                                                        Número do Documento.|Campo do tipo caracter, de tamanho 20.            OPERACIONAL                        NaN
PCLFREGE340    NUMPROC VARCHAR2(20)                                          Número do Processo, se for o caso.|Campo do tipo caracter, de tamanho 20.            OPERACIONAL                        NaN
PCLFREGE340  INDORIGEM  NUMBER(3,0) Indicador de Origem conforme manual do Livro Eletrônico.|Campo do tipo numérico, de tamanho 3, sem casas decimais.            OPERACIONAL                        NaN
PCLFREGE340   DESCPROC VARCHAR2(80)                                       Descrição do Processo, se for o caso.|Campo do tipo caracter, de tamanho 80.            OPERACIONAL                        NaN
PCLFREGE340 REFERENCIA VARCHAR2(50)                                        Descrição de Referência do Processo.|Campo do tipo caracter, de tamanho 50.            OPERACIONAL                        NaN
PCLFREGE340  CODAJUSTE  VARCHAR2(8)                                                                                                                NaN            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*