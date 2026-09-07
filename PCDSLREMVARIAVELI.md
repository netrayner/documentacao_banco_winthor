# 📊 Tabela: PCDSLREMVARIAVELI

### Estrutura de Colunas e Restrições

           Tabela        Coluna Tipo/Tamanho                          Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCDSLREMVARIAVELI    IDAPURACAO  NUMBER(8,0) Identificação apuração remuneração variável. CHAVE ESTRANGEIRA (FK)          PCDSLREMVARIAVELC
PCDSLREMVARIAVELI       CODUSUR  NUMBER(4,0)                               Código do RCA.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI   VLVENDAPREV NUMBER(18,4)                            Meta valor venda.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI    VLFATURADO NUMBER(18,4)                    Realizado valor faturado.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI        PREMIO NUMBER(18,4)                             Valor do prêmio.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI  TIPOAPURACAO  NUMBER(1,0)                               Tipo apuração.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI     CODFORNEC  NUMBER(6,0)                        Código do fornecedor.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI       MIXPREV  NUMBER(6,0)                                    Meta mix.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI      QTPONTOS  NUMBER(8,2)                        Quantidade de pontos.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI        CLIPOS  NUMBER(6,0)              Realizado clientes positivados.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI    CLIPOSPREV  NUMBER(6,0)                   Meta clientes positivados.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI VLMINVENDAPOS  NUMBER(8,0)   Meta valor mínimo da venda para positivar.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI       CONTMIX  NUMBER(6,0)                                Contagem mix.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI      CODLINHA  NUMBER(6,0)                     Código linha de produto.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI       CODPROD  NUMBER(6,0)                           Código do produto.            OPERACIONAL                        NaN
PCDSLREMVARIAVELI       CODRAMO  NUMBER(6,0)                    Código ramo de atividade.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*