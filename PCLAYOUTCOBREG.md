# 📊 Tabela: PCLAYOUTCOBREG

### Estrutura de Colunas e Restrições

        Tabela           Coluna  Tipo/Tamanho                                                                                     Descrição da Coluna Restrição (Constraint) Tabela Relacionada (Se FK)
PCLAYOUTCOBREG           CODIGO   NUMBER(8,0)                                                                                                  Codigo    CHAVE PRIMÁRIA (PK)                        NaN
PCLAYOUTCOBREG     CODLAYOUTMAG        NUMBER                                                               Ligação com o layout de arquivo magnético CHAVE ESTRANGEIRA (FK)                PCLAYOUTCOB
PCLAYOUTCOBREG             LOTE        NUMBER                                                                                                    Lote            OPERACIONAL                        NaN
PCLAYOUTCOBREG     TIPOREGISTRO   VARCHAR2(2) HA - Header de arquivo, HL - Header de lote, D - Detalhe, TL - Trailer de lote, TA - Trailer de arquivo            OPERACIONAL                        NaN
PCLAYOUTCOBREG CODTIPOPAGAMENTO        NUMBER                                                                             Codigo do tipo do pagamento CHAVE ESTRANGEIRA (FK)               PCFORMAPAGTO
PCLAYOUTCOBREG         SEGMENTO   VARCHAR2(5)                          A identificação do segmento é uma letra. Um lote pode conter vários segmentos.            OPERACIONAL                        NaN
PCLAYOUTCOBREG    ORDEMDETALHES        NUMBER                                                                                       Ordem de detalhes            OPERACIONAL                        NaN
PCLAYOUTCOBREG     VARQUEFALTAM VARCHAR2(200)                                      Listas de variáveis obrigatórias que faltam nas posições do layout            OPERACIONAL                        NaN

---
*Documentação gerada automaticamente.*