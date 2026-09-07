# 📊 Tabela: PCSUGESTAOREPOSICAOMEDFTA

### Estrutura de Colunas e Restrições

                   Tabela                 Coluna  Tipo/Tamanho                 Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCSUGESTAOREPOSICAOMEDFTA         NUMSUGESTAOREP  NUMBER(12,0)                  Número da Sugestão    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDFTA               SEQFALTA   NUMBER(9,0)                          Seq. Falta    CHAVE PRIMÁRIA (PK)                        NaN
PCSUGESTAOREPOSICAOMEDFTA         CODFILIALFALTA   VARCHAR2(2) Código da Filial onde ocorreu Falta            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA           CODPRODFALTA   NUMBER(6,0)                Código Produto Falta            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA              CODFORNEC   NUMBER(6,0)                   Código Fornecedor            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA                 CODCLI   NUMBER(6,0)                   Código do Cliente            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA                QTFALTA  NUMBER(22,6)                         Qtde. Falta            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA            CODFILIAL_O   VARCHAR2(2)                Código Filial Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA              CODPROD_O   NUMBER(6,0)               Código Produto Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA              QTFALTA_O  NUMBER(22,6)                  Qtde. Falta Origem            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA            CODFILIAL_D   VARCHAR2(2)               Código Filial Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA              CODPROD_D   NUMBER(6,0)                  Cód. Prod. Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA              QTFALTA_D  NUMBER(22,6)                 Qtde. Falta Destino            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA                 NUMPED  NUMBER(11,0)                       Número Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA                  QTPED  NUMBER(22,6)                        Qtde. Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA               PRECOPED  NUMBER(22,6)                        Preço Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA            NUMSUGESTAO  NUMBER(10,0)              Número Sugestão Compra            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA               DTGERPED          DATE                 Data Geração Pedido            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA        REJEICAOINICIAL   VARCHAR2(1)                       Flag Rejeição            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA     OBSERVACAOREJEICAO VARCHAR2(240)                 Observação Rejeição            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA    CODFORNECPRIORIDADE   NUMBER(6,0)        Código Fornecedor Prioridade            OPERACIONAL                        NaN
PCSUGESTAOREPOSICAOMEDFTA TIPO_SUG_COMPRA_TRANSF   VARCHAR2(1)     Tipo Sugestão Compra ou Transf.            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*