# 📊 Tabela: PCNFENTXML

### Estrutura de Colunas e Restrições

    Tabela      Coluna Tipo/Tamanho                                                                            Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFENTXML        CNPJ VARCHAR2(18)                                       Gravar o CNPJ do Fornecedor\tGravar o CNPJ do Fornecedor            OPERACIONAL                        NaN
PCNFENTXML     NUMNOTA NUMBER(10,0) Gravar o número da nota que está dando entrada\tGravar o número da nota que está dando entrada            OPERACIONAL                        NaN
PCNFENTXML       SERIE  VARCHAR2(3)                           Gravar a série da nota de entrada\tGravar a série da nota de entrada            OPERACIONAL                        NaN
PCNFENTXML   DTEMISSAO         DATE       Gravar a data de emissão da nota de entrada\tGravar a data de emissão da nota de entrada            OPERACIONAL                        NaN
PCNFENTXML    DADOSXML         CLOB                                                 Gravar os dados do XML\tGravar os dados do XML            OPERACIONAL                        NaN
PCNFENTXML NUMTRANSENT NUMBER(10,0)                                                     Gravar o NUMTRANSENT\tGravar o NUMTRANSENT            OPERACIONAL                        NaN
PCNFENTXML        DATA         DATE                               Gravar a Data de entrada do XML\tGravar a Data de entrada do XML            OPERACIONAL                        NaN
PCNFENTXML     CODFUNC NUMBER(10,0)                   Gravar o Cód. Func que fez a operação\tGravar o Cód. Func que fez a operação            OPERACIONAL                        NaN
PCNFENTXML    CHAVENFE VARCHAR2(44)                                                                                      Chave NFe            OPERACIONAL                        NaN
PCNFENTXML   CODFORNEC  NUMBER(7,0)                                                                           Código do fornecedor            OPERACIONAL                        NaN
PCNFENTXML LOG_PROCESS         CLOB                                                    Log dos possíveis motivos da não importação            OPERACIONAL                        NaN
PCNFENTXML    SITUACAO  VARCHAR2(1)                                                              Situação da importação automatica            OPERACIONAL                        NaN
PCNFENTXML       ORDEM  NUMBER(4,0)                                                                            Ordem da importação            OPERACIONAL                        NaN
PCNFENTXML  DTCADASTRO         DATE                                                                        Data de inclusão do XML            OPERACIONAL                        NaN
PCNFENTXML  TENTATIVAS  NUMBER(5,0)                                                           Número de tentaivas de processamento            OPERACIONAL                        NaN
PCNFENTXML  NATOPERNFE VARCHAR2(60)                                                                           Natureza da operação            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*