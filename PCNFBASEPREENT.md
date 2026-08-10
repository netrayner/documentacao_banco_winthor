# 📊 Tabela: PCNFBASEPREENT

### Estrutura de Colunas e Restrições

        Tabela                Coluna Tipo/Tamanho                                                                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCNFBASEPREENT              ALIQUOTA  NUMBER(5,2)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT                VLBASE NUMBER(12,2)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT         NUMTRANSVENDA NUMBER(10,0)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT                VLICMS NUMBER(12,2)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT           NUMTRANSENT NUMBER(10,0)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT               CODCONT NUMBER(10,0)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT             CODFISCAL  NUMBER(8,0)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT              VLBASENF NUMBER(12,2)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT                  TIPO  VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT             VLISENTAS NUMBER(12,2)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT            TIPOPREENT  VARCHAR2(1)                                                                                 NaN            OPERACIONAL                        NaN
PCNFBASEPREENT   DTEXPORTACAOSERVINT         DATE                          Indica a data da exportação para o servidor intermediario.            OPERACIONAL                        NaN
PCNFBASEPREENT DTIMPORTACAOSERVPRINC         DATE                                Indica a data de importação pelo servidor principal.            OPERACIONAL                        NaN
PCNFBASEPREENT      EXPORTADOSERVINT  VARCHAR2(1)                                Indica se foi exportado pelo servidor intermediario.            OPERACIONAL                        NaN
PCNFBASEPREENT    IMPORTADOSERVPRINC  VARCHAR2(1)                                    Indica se foi importado pelo servidor principal.            OPERACIONAL                        NaN
PCNFBASEPREENT              VLMEXIVA NUMBER(12,2) Valor de IVA informado para NFs de consumo/imobilizado (quando a NF não tem itens).            OPERACIONAL                        NaN
PCNFBASEPREENT   GERAICMSLIVROFISCAL  VARCHAR2(1)                                                           GERA ICMS NO LIVRO FISCAL            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*