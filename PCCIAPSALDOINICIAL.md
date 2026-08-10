# 📊 Tabela: PCCIAPSALDOINICIAL

### Estrutura de Colunas e Restrições

            Tabela                      Coluna Tipo/Tamanho                         Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCCIAPSALDOINICIAL                    CODSALDO  NUMBER(6,0)              Indica o código saldo inicial.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIAPSALDOINICIAL                   CODFILIAL  VARCHAR2(2)                  Indica o código da filial.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                        DATA         DATE                   Indica o data da entrada.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                     NUMNOTA NUMBER(10,0)                    Indica o número da nota.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                     CODPROD  NUMBER(6,0)                 Indica o código do produto.    CHAVE PRIMÁRIA (PK)                        NaN
PCCIAPSALDOINICIAL                   VLCREDITO NUMBER(12,2)             Indica o valor do crédito CIAP.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL               DTTERMINOCIAP         DATE                 Indica a data termino CIAP.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL          VLRDEPRECACUMULADA NUMBER(24,2)    Indica o valor da depreciação acumulada.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                 VLRATUALBEM NUMBER(24,2)                Indica o valor atual do bem.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL               NUMPATRIMONIO VARCHAR2(20)              Indica o número do patrimonio.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                   DATABAIXA         DATE                     Indica a data da baixa.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                   TIPOBAIXA  VARCHAR2(2)                     Indica o tipo da baixa.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL               NUMTRANSVENDA NUMBER(10,0)      Indica o número da transação de venda.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL             TAXADEPRECIACAO NUMBER(12,2)               Indica a taxa de depreciação.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL              QTDTRANSFERIDA NUMBER(16,4)              Quantidade transferida do bem.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL          DATAULTDEPRECIACAO         DATE                 Data da última depreciação.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL           CODRESPONSAVELBEM  NUMBER(6,0)                Código responsável pelo bem.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL           CODLOCALIZACAOBEM  NUMBER(6,0)                  Código localização do bem.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                   CODFORNEC  NUMBER(6,0)                          Código Fornecedor.            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                  TIPOMOVBEM  VARCHAR2(2)                 Tipo de movimentação do bem            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL             CODBEMPRINCIPAL  NUMBER(6,0)                     Código do bem principal            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL              VLRBEMRESIDUAL NUMBER(22,2)                              Valor residual            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL                 VLCORRIGIDO NUMBER(22,2)                      Valor do bem corrigido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL              VLCORRIGIDORES NUMBER(22,2)                    Valor residual corrigido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL    TAXADEPRECIACAOCORRIGIDO NUMBER(12,2)         Taxa de Depreciação valor corrigido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL VLRDEPRECACUMULADACORRIGIDO NUMBER(22,2) Valor da deprec. Acum. Pelo valor corrigido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL              VLBEMATRIBUIDO NUMBER(22,2)                      Valor do bem atribuido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL             VLRATRIBUIDORES NUMBER(22,2)                    Valor residual atribuido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL    TAXADEPRECIACAOATRIBUIDO NUMBER(12,2)         Taxa de Depreciação valor atribuido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL VLRDEPRECACUMULADAATRIBUIDO NUMBER(22,2) Valor da deprec. Acum. Pelo valor atribuido            OPERACIONAL                        NaN
PCCIAPSALDOINICIAL               VLDIFALIQUOTA NUMBER(16,2)               Valor diferencial de aliquota            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*