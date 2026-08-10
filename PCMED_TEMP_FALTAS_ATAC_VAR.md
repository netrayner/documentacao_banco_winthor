# 📊 Tabela: PCMED_TEMP_FALTAS_ATAC_VAR

### Estrutura de Colunas e Restrições

                    Tabela                 Coluna  Tipo/Tamanho             Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCMED_TEMP_FALTAS_ATAC_VAR         NUMSUGESTAOREP  NUMBER(12,0)              Sugestão Reposição            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR               SEQFALTA   NUMBER(9,0)              Sequência da Falta            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR         CODFILIALFALTA   VARCHAR2(2)       Código da Filial da Falta            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR           CODPRODFALTA   NUMBER(6,0)            Código Produto Falta            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR              CODFORNEC   NUMBER(6,0)                 Cód. Fornecedor            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR                 CODCLI   NUMBER(6,0)               Código do Cliente            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR                QTFALTA  NUMBER(22,6)                     Qtde. Falta            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR            CODFILIAL_O   VARCHAR2(2)             Código Filia Origem            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR              CODPROD_O   NUMBER(6,0)           Código Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR              QTFALTA_O  NUMBER(22,6)      Qtde. Falta Produto Origem            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR            CODFILIAL_D   VARCHAR2(2)           Código Filial Destino            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR              CODPROD_D   NUMBER(6,0)          Código Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR              QTFALTA_D  NUMBER(22,6)     Qtde. Falta Produto Destino            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR                 NUMPED  NUMBER(11,0)                   Pedido Gerado            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR                  QTPED  NUMBER(22,6)                    Qtde. Pedido            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR               PRECOPED  NUMBER(22,6)                    Preço Pedido            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR            NUMSUGESTAO  NUMBER(10,0)              Sugestão de Compra            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR               DTGERPED          DATE             Data Geração Pedido            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR        REJEICAOINICIAL   VARCHAR2(1)           Flag Rejeição Inicial            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR     OBSERVACAOREJEICAO VARCHAR2(240)          Observação da Rejeição            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR    CODFORNECPRIORIDADE   NUMBER(6,0)      Cód. Fornecedor Prioridade            OPERACIONAL                        NaN
PCMED_TEMP_FALTAS_ATAC_VAR TIPO_SUG_COMPRA_TRANSF   VARCHAR2(1) Tipo Sugestão Compra ou Transf.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*