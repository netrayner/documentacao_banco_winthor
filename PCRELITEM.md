# 📊 Tabela: PCRELITEM

### Estrutura de Colunas e Restrições

   Tabela               Coluna  Tipo/Tamanho                                       Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCRELITEM              CODITEM   NUMBER(8,0)                                           Código do Item.    CHAVE PRIMÁRIA (PK)                        NaN
PCRELITEM             CODGRUPO   NUMBER(8,0)                                          Código do Grupo.            OPERACIONAL                        NaN
PCRELITEM                ORDEM   NUMBER(3,0)                                            Ordem do Item.            OPERACIONAL                        NaN
PCRELITEM            DESCRICAO  VARCHAR2(80)                                                Descrição.            OPERACIONAL                        NaN
PCRELITEM        TIPOMOVIMENTO   VARCHAR2(1)                                           Tipo Movimento.            OPERACIONAL                        NaN
PCRELITEM     CRITERIO_ESPECIE   VARCHAR2(2)                                          Critério Espécie            OPERACIONAL                        NaN
PCRELITEM       CRITERIO_SERIE   VARCHAR2(2)                                   Indica o critério série            OPERACIONAL                        NaN
PCRELITEM  CRITERIO_TIPOPESSOA   VARCHAR2(1)                                      Critério Tipo Pessoa            OPERACIONAL                        NaN
PCRELITEM    CRITERIO_OPERACAO   VARCHAR2(1)                                         Critério Operação            OPERACIONAL                        NaN
PCRELITEM        CRITERIO_CFOP  VARCHAR2(10)                                             Critério CFOP            OPERACIONAL                        NaN
PCRELITEM           LISTA_CFOP  VARCHAR2(80)                                            Lista de CFOPs            OPERACIONAL                        NaN
PCRELITEM    CRITERIO_ALIQUOTA  VARCHAR2(10)                                         Critério Aliquota            OPERACIONAL                        NaN
PCRELITEM       LISTA_ALIQUOTA  VARCHAR2(80)                                       Lista de Alíquotas.            OPERACIONAL                        NaN
PCRELITEM     VLCONTABILMANUAL  NUMBER(16,2)                                       Vl.Contábil Manual.            OPERACIONAL                        NaN
PCRELITEM         VLBASEMANUAL  NUMBER(16,2)                                           Vl.Base Manual.            OPERACIONAL                        NaN
PCRELITEM         VLICMSMANUAL  NUMBER(16,2)                                           Vl.ICMS Manual.            OPERACIONAL                        NaN
PCRELITEM     EXPRESSAO_VLICMS VARCHAR2(200)            Indica o campo que guarda a expressão de ICMS.            OPERACIONAL                        NaN
PCRELITEM     EXPRESSAO_VLBASE VARCHAR2(200) Indica o campo que guarda a expressão da base de calculo.            OPERACIONAL                        NaN
PCRELITEM EXPRESSAO_VLCONTABIL VARCHAR2(200)  Indica o campo que guarda a expressão do valor contábil.            OPERACIONAL                        NaN
PCRELITEM             NEGATIVO   VARCHAR2(1)                   Indica se converte o valor em negativo.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*