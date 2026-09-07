# 📊 Tabela: PCLFREGE350

### Estrutura de Colunas e Restrições

     Tabela           Coluna Tipo/Tamanho                                                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLFREGE350           CODREG  NUMBER(6,0)                                       Código do Registro.|Campo do tipo numérico, de tamanho 6, sem casas decimais.    CHAVE PRIMÁRIA (PK)                        NaN
PCLFREGE350        CODFILIAL  VARCHAR2(2)                                           Código da Filial do relacionamento.|Campo do tipo caracter, de tamanho 2.            OPERACIONAL                        NaN
PCLFREGE350             DATA         DATE                                                                 Data do Lançamento do registro.|Campo do tipo data.            OPERACIONAL                        NaN
PCLFREGE350         CODOBRIG  NUMBER(6,0) Código da Obrigação, conforme manual do Livro Eletrônico.|Campo do tipo numérico, de tamanho 6, sem casas decimais.            OPERACIONAL                        NaN
PCLFREGE350          VLOBRIG NUMBER(15,2)                                    Valor da Obrigação.|Campo do tipo numérico, de tamanho 15, com 2 casas decimais.            OPERACIONAL                        NaN
PCLFREGE350            DTDOC         DATE                                                                              Data do Documento.|Campo do tipo data.            OPERACIONAL                        NaN
PCLFREGE350           CODREC VARCHAR2(10)                 Código do Recolhimento, conforme manual do Livro Eletrônico.|Campo do tipo caracter, de tamanho 10.            OPERACIONAL                        NaN
PCLFREGE350            UFDOC  VARCHAR2(2)                                            Unidade de Federação do Documento.|Campo do tipo caracter, de tamanho 2.            OPERACIONAL                        NaN
PCLFREGE350          NUMPROC VARCHAR2(60)                                           Número do Processo, se for o caso.|Campo do tipo caracter, de tamanho 20.            OPERACIONAL                        NaN
PCLFREGE350        INDORIGEM  NUMBER(3,0)  Indicador de Origem conforme manual do Livro Eletrônico.|Campo do tipo numérico, de tamanho 3, sem casas decimais.            OPERACIONAL                        NaN
PCLFREGE350         DESCPROC VARCHAR2(80)                                        Descrição do Processo, se for o caso.|Campo do tipo caracter, de tamanho 80.            OPERACIONAL                        NaN
PCLFREGE350       REFERENCIA VARCHAR2(50)                                         Descrição de Referência do Processo.|Campo do tipo caracter, de tamanho 50.            OPERACIONAL                        NaN
PCLFREGE350 TIPORECOLHIMENTO  VARCHAR2(5)                                                                                      Indica o tipo de recolhimento.            OPERACIONAL                        NaN
PCLFREGE350          MES_REF  VARCHAR2(6)                                                                                                   Mês de referencia            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*