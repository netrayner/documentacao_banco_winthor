# 📊 Tabela: PCAJUSTEPERSONALIZADOC197

### Estrutura de Colunas e Restrições

                   Tabela               Coluna Tipo/Tamanho                             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCAJUSTEPERSONALIZADOC197               CODIGO  NUMBER(9,0)                       Identificador do registro            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197            CODFILIAL  VARCHAR2(2)                                Código da filial            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197             OPERACAO  VARCHAR2(1)                               Define a operação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197         TIPOOPERACAO  VARCHAR2(2)                      Define do tipo da operação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197           TIPOPESSOA  VARCHAR2(1)     Define o tipo da pessoa, Física ou Jurídica            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197     DTVIGENCIAINICIO         DATE                    Data de Inicio da legislação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197        DTVIGENCIAFIM         DATE                       Data de fim da legislação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197            CODIGOOBS  VARCHAR2(6)                            Código da observação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197         DESCRICAOOBS VARCHAR2(80)                         Descrição da observação            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197         CODIGOAJUSTE VARCHAR2(10)                                Código do ajuste            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197     FINALIDADEAJUSTE VARCHAR2(80)                            Finalidade do ajuste            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197     TIPOBASECALCICMS  VARCHAR2(2)              Tipo de base de cálculo será usada            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197     TIPOALIQUOTAICMS  VARCHAR2(2)          Tipo de alíquota será usada no cálculo            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197       VLALIQUOTAICMS NUMBER(18,4)                    Valor da aliquota específica            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197  GERAVALORICMSOUTROS  VARCHAR2(1)           Define se irá gerar em ICMS ou OUTROS            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197                  SQL         CLOB                   SQL gerado conforme marcações            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197  GERABASECALCULONULL  VARCHAR2(1)              Determina gerar a base nula ou não            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197 GERAALIQUOTAICMSNULL  VARCHAR2(1)  Determina gerar a aliquota de icms nula ou não            OPERACIONAL                        NaN
PCAJUSTEPERSONALIZADOC197            DEVFORNEC  VARCHAR2(1) DEFINE SE A SAIDA É UMA DEVOLUÇÃO DE FORNECEDOR            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*